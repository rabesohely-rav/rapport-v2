# Rapport d'activité annuel – France Services V2

Version V2, pensée pour rester simple et utile.

## Ce que fait cette version

- filtre par date de début
- filtre par date de fin
- filtre par nom de France Services
- sélection du Top N (3, 5 ou 10)
- KPI recalculés
- graphiques dynamiques
- tableau détaillé
- bouton **Exporter en PDF**

## Structure

```text
.
├── index.html
└── data/
    └── data.csv
```

## Utilisation

1. Remplace `data/data.csv` par ton nouveau CSV.
2. Garde exactement ce nom : `data.csv`.
3. Push sur GitHub.
4. Ouvre GitHub Pages.
5. Applique les filtres.
6. Clique sur **Exporter en PDF**.

## Colonnes minimales requises

- `date_creation`
- `nom_FS`
- `id_usager`
- `primo_usager`

## Colonnes utiles pour les graphiques supplémentaires

- `thematique`
- `statut_activite`

## GitHub Pages

1. Crée un dépôt GitHub
2. Dépose le contenu de ce dossier à la racine
3. Va dans **Settings > Pages**
4. Choisis **Deploy from a branch**
5. Branche `main`, dossier `/root`
6. Sauvegarde

## Important

Le modèle suppose un CSV séparé par des points-virgules `;`.
