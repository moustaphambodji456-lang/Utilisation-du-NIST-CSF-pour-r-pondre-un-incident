# Utilisation-du-NIST-CSF-pour-repondre-un-incident
Projet réalisé lors de la certification Google Cybersecurity, mettant en pratique les notions en réponse d'incident et de la connaissance du framework NIST-CSF
 # Contexte
Nous sommes analyste en cybersécurité travaillant pour une entreprise multimédia qui propose des services de conception web, de graphisme et des solutions de marketing pour les médias sociaux aux petites entreprises. Votre organisation a récemment subi une attaque DDoS, qui a compromis le réseau interne pendant deux heures jusqu'à ce qu'elle soit résolue.

Au cours de l'attaque, les services réseau de votre organisation ont soudainement cessé de répondre en raison d'une Inondation ICMP entrante. Le trafic normal du réseau interne ne pouvait accéder à aucune ressource du réseau. L'équipe de gestion des incidents a réagi en bloquant les paquets ICMP entrants, en arrêtant tous les services réseau non critiques hors ligne et en rétablissant les services réseau critiques.

L'équipe de cybersécurité de l'entreprise a ensuite enquêté sur l'événement de sécurité. Elle a découvert qu'un acteur malveillant avait envoyé un flot de pings ICMP dans le réseau de l'entreprise par l'intermédiaire d'un pare-feu non configuré. Cette vulnérabilité a permis à l'attaquant malveillant de submerger le réseau de l'entreprise par le biais d'une attaque par déni de service distribué (DDoS).

Pour remédier à cet événement, l'équipe chargée de la sécurité du réseau a mis en œuvre les mesures suivantes

Une nouvelle règle de pare-feu pour limiter le taux de paquets ICMP entrants

Une vérification de l'adresse IP source sur le pare-feu afin de détecter les adresses IP usurpées dans les paquets ICMP entrants

Un logiciel de surveillance du réseau pour détecter les schémas de trafic anormaux

Un système IDS/IPS pour filtrer une partie du trafic ICMP sur la base de caractéristiques suspectes

En tant qu'analyste en cybersécurité, nous sommes chargés d'utiliser cet événement de sécurité pour élaborer un plan visant à améliorer la sécurité du réseau de votre entreprise, conformément au Cadre de cybersécurité (CSF) du NIST (National Institute of Standards and Technology). Nous utiliserons le CSF pour nous aider à parcourir les différentes étapes de l'analyse de cet événement de cybersécurité et à intégrer votre analyse dans une stratégie de sécurité générale.
# Analyse
Vous pouvez vérifier le travail effectué dans le fichier Incident Report Analysis ci-dessus.
