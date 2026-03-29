# Normalisation de Données Patrimoniales

## 📌 Objectif du projet
Restructurer des bases de données brutes pour assurer leur interopérabilité et leur pérennité sur la plateforme **NAKALA**.

## ⚙️ Travail réalisé
1. **Audit de données :** Identification des doublons et des incohérences.
2. **Modélisation :** Passage d'un format plat à un modèle relationnel optimisé (**3NF**).
3. **Qualité :** Nettoyage (ETL) et enrichissement des métadonnées selon le standard **Dublin Core**.
4. **Diffusion :** Préparation des packages de données pour un archivage conforme aux principes **FAIR**.

## 🛠 Outils utilisés
- **SQL / PostgreSQL**
- **Python (Pandas)**
- **Plateforme NAKALA**

ENTREPOT/
│
├── donnes_normalisees/
│   ├── activites.csv
│   ├── domaine.csv
│   ├── etablissements.csv
│   ├── lieux.csv
│   ├── objets.csv
│   ├── objets_activites.csv
│   ├── objets_domaines.csv
│   ├── objets_etablissements.csv
│   ├── objetspersonnes.csv
│   └── personnes.csv
│
├── Dictionnaire_de_donnes.xlsx
├── Tableau_transformation.xlsx
├── Tableau_dublin_core.xlsx
├── Rapport_final.docx
├── MLD.png 
└── readme
