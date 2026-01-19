# TP-DNS-APACHE-UBUNTU
# Configuration d'un Serveur Web (Apache) et DNS (Bind9) sur Ubuntu

## Objectifs
Mettre en place une infrastructure réseau locale permettant d'accéder à un site web via un nom de domaine personnalisé (`monprojet.local`) au lieu d'une adresse IP.

## Technologies Utilisées
* **OS :** Ubuntu 22.04 LTS (via virtualisation UTM sur macOS)
* **Serveur Web :** Apache2
* **Serveur DNS :** BIND9
* **Réseau :** Configuration d'enregistrements A et de forwarders DNS

## Instructions pour exécuter le projet
1. Installer Apache et Bind9 : `sudo apt install apache2 bind9`
2. Copier les fichiers de configuration DNS du dossier `/config-dns` vers `/etc/bind/` sur Ubuntu.
3. Copier le fichier HTML du dossier `/config-apache` vers `/var/www/html/`.
4. Redémarrer les services : `sudo systemctl restart apache2 bind9`.
5. Configurer le DNS du client (Mac/PC) avec l'IP de la machine Ubuntu.

## Membres du groupe
* ONDO NDONG SAMUEL JEAMIR
* LENGADIO MICHAEL
