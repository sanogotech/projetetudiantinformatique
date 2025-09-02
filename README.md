# Projetetudiantinformatique


# Projets Tutorés (120h) - Licence Professionnelle CNAM Web Mobile et BI

## Répartition indicative des 120h par projet

- **Étude préalable, cadrage fonctionnel & technique :** 20h
- **Conception technique & modélisation (BDD, IHM, architecture) :** 20h
- **Développement & intégration :** 50h
- **Tests, documentation, corrections :** 15h
- **Préparation soutenance, rapport, démo :** 15h

---

## Catégorie 1 : Business Intelligence & Data Mining

### 1. Tableau de bord décisionnel RH
#### Objectif :
Mettre en place un tableau de bord RH intégrant l’absentéisme, la masse salariale, les départs, recrutements, etc.
#### Technologies : Power BI / Metabase / PostgreSQL / ETL Talend ou Apache Nifi
#### Détails supplémentaires :
- Étude des indicateurs RH clés et définition des KPIs avec un expert RH
- Réalisation d’un schéma étoile ou en flocon
- Connecteurs vers CSV, API, ERP fictif
- Création de 3 tableaux de bord dynamiques (par période, par service, par salarié)
- Génération de rapports PDF automatisés
- Livrables : MCD, script BDD, rapport d'analyse, dashboards, manuel utilisateur

### 2. Data Mining prédictif de l’attrition client

#### Objectif :
Créer un modèle de scoring pour prédire la perte de clients d’une entreprise de services
#### Technologies : Python / Scikit-learn / Jupyter / Pandas
#### Détails supplémentaires :
- Jeu de données synthétique à nettoyer et enrichir
- Exploration de variables explicatives et analyse corrélative
- Utilisation de plusieurs modèles (régression logistique, arbres, KNN...)
- Mesure de performance (accuracy, F1-score, confusion matrix)
- Visualisation des résultats avec Dash ou Streamlit

---

## Catégorie 2 : Développement Web et Mobile

### 3. Application de gestion d’événements sportifs
#### Objectif :
Plateforme web et mobile pour inscrire des équipes, gérer les matchs, scores, et classements.
#### Technologies : Flutter / Firebase / Node.js / MongoDB
#### Détails supplémentaires :
- Authentification par rôle : admin, organisateur, participant
- Interface mobile-first et responsive
- Génération dynamique de tournois en round-robin ou élimination directe
- Historique des résultats, gestion des sanctions/cartons
- Export CSV des résultats et dashboard admin

### 4. Plateforme d’offres d’emploi pour freelances
#### Objectif :
Développement d’un site où freelances peuvent créer un profil, postuler et suivre les missions
#### Technologies : Vue.js / Express.js / MySQL / REST API
#### Détails supplémentaires :
- Création de profils, CV PDF dynamiques
- Gestion de matching entre profils et offres par mots-clés ou tags
- Tableau de bord de suivi de candidature
- Chat simple entre recruteur et freelance

---

## Catégorie 3 : Administration Systèmes & Sécurité

### 5. Homelab distant sécurisé pour 20-50 étudiants
#### Objectif :
Mettre en place une infrastructure distante accessible par navigateur pour pratiquer des TP sur des machines virtuelles.
#### Technologies : Proxmox / Guacamole / WireGuard / Docker
#### Détails supplémentaires :
- Déploiement de VMs Ubuntu & Windows, snapshot + clonage
- Portail sécurisé avec authentification + VPN
- Scripts d’automatisation de déploiement et reset
- Suivi des connexions et sécurité renforcée
- Accès partagé par groupe (binômes)

### 6. Simulateur d’attaques réseau & détection IDS
#### Objectif :
Créer une plateforme d’analyse de sécurité simulant des intrusions détectées par un IDS open-source
#### Technologies : Kali Linux / Suricata / Zeek / ELK Stack
#### Détails supplémentaires :
- Mise en place de scénarios d’attaque (DoS, brute force, phishing)
- Collecte des logs en temps réel, visualisation avec Kibana
- Rapport sur les types d’attaques, réactions de l’IDS
- Recommandations de protection

---

## Catégorie 4 : Systèmes d’Information & Gestion

### 7. Système de gestion des congés & absences
#### Objectif :
Système d’information de gestion RH des congés avec circuit de validation
#### Technologies : Laravel / PostgreSQL / Bootstrap
#### Détails supplémentaires :
- Workflow d’approbation par manager RH
- Notifications par email
- Rapport annuel de congés consommés / soldes
- Statistiques de comparaison entre services

### 8. Gestion électronique des documents (GED)
#### Objectif :
Créer un système de GED simplifié pour PME
#### Technologies : Symfony / Elasticsearch / MongoDB
#### Détails supplémentaires :
- Indexation des documents par mots-clés, OCR
- Arborescence hiérarchique personnalisée
- Recherche full-text rapide
- Journal d’accès et versionning

---

## Catégorie 5 : Projets Innovants & Transverses

### 9. Assistant vocal métier (support RH ou commercial)
#### Objectif :
Créer un assistant vocal qui répond à des questions métier courantes (recrutement, contrats, support)
#### Technologies : Python / Dialogflow / Flask API / Google Speech-to-Text
#### Détails supplémentaires :
- Dialogue contextuel basé sur FAQ métier
- Voix synthétique + reconnaissance vocale
- Interface Web de gestion des questions / réponses

### 10. Application d’analyse de performance scolaire
#### Objectif :
Créer un outil de suivi de performance pour établissements secondaires (profils étudiants, moyennes, prédictions)
#### Technologies : Django / SQLite / Chart.js / Pandas
#### Détails supplémentaires :
- Import Excel des notes par matière / trimestre
- Dashboards pour parents, enseignants, direction
- Génération de bulletins et recommandations pédagogiques
- Algorithme simple de prédiction d’échec (ML ou règle métier)
