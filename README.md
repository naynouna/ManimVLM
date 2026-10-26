# Critique visuelle (VLM) pour la génération d'animations Manim

Projet de fin d'études (420-A63-BB), Imen Ben Yahia, AEC Spécialisation technique en IA, Collège de Bois-de-Boulogne.
Stage réalisé à distance au centre de recherche I2A, Université TÉLUQ.

## Question de recherche

Est-ce qu'une critique faite par un modèle vision-langage (VLM) améliore le taux de rendus réussis (RSR) et la similarité visuelle (VS) par rapport à RITL-DOC seul ?

## Contenu

| Fichier | Rôle |
|---|---|
| `notebooks/notebook_1_generateur_3B.ipynb` | Générateur 3B + VLM 2B : vanilla, RITL, RITL-DOC, RITL-DOC + VLM |
| `notebooks/notebook_2_generateur_7B.ipynb` | Générateur 7B + VLM 7B : RITL-DOC et RITL-DOC + VLM |
| `notebooks/notebook_3_interface.ipynb` | Interface de démonstration (Gradio) |

## Utilisation

Ouvrir un notebook sur Kaggle et lancer les cellules. Pour l'interface, ouvrir le lien `gradio.live` affiché sous la dernière cellule.

## Source des données et licence

Les 100 exemples de test viennent de ManimBench, téléchargés pendant l'exécution depuis le dépôt de l'article
« Training and Agentic Inference Strategies for LLM-based Manim Animation Generation » (Rammuni Silva et al., 2026, arXiv:2604.18364, CC BY-NC-SA 4.0).
Ni les données ni le code des auteurs ne sont copiés dans ce dépôt.
Les méthodes RITL et RITL-DOC viennent de cet article ; le code de ce dépôt est une réécriture simplifiée.
