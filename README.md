# Git repo to deploy my application stack automaticaly. 

## Organization : 
Tree  
├── README.md  
├── apps  
│   ├── README.md  
│   ├── bitwarden  
│   │   └── docker-compose.yml  
│   ├── freshrss  
│   │   └── docker-compose.yml  
│   ├── mail  
│   │   └── docker-compose.yml  
│   ├── nextcloud  
│   │   └── docker-compose.yml  
│   ├── prometheus  
│   │   └── docker-compose.yml  
│   └── statping  
│       └── docker-compose.yml  
└── core  
    └── docker-compose.yml  

## Components: 
core : 
- traefik
- portainer
- watchtower

apps :
- bitwarden
- freshrss
- mail
    - mailserver
    - rainloop
- nextcloud
    - nextcloud
    - mariadb
    - redis
- prometheus
    - prometheus
    - grafana
    - cadvisor
    - node-exporter
- statping