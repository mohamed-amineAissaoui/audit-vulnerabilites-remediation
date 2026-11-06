# Audit de vulnérabilités et plan de correction

## Présentation du projet

Ce projet est réalisé dans le cadre de ma deuxième année de BTS SIO, option SISR.

Il consiste à réaliser un audit de vulnérabilités sur un environnement informatique composé de plusieurs machines virtuelles. Le but est d'identifier les failles de sécurité, d'évaluer les risques et de proposer des corrections adaptées.

Le projet reprend le contexte d'une collectivité de 40 agents qui doit effectuer un scan de vulnérabilités tous les six mois à la demande de son assureur cyber.

L'objectif est de rendre les résultats de l'audit compréhensibles et de permettre au directeur de savoir quelles vulnérabilités doivent être corrigées en priorité.

## Objectifs du projet

- Installer et configurer un scanner de vulnérabilités avec Greenbone.
- Effectuer un premier scan sur quatre machines virtuelles.
- Analyser les résultats et identifier les vulnérabilités.
- Classer les failles selon leur score CVSS et leur niveau d'exposition.
- Définir les dix vulnérabilités à corriger en priorité.
- Corriger au minimum cinq vulnérabilités.
- Effectuer un second scan pour vérifier les corrections.
- Comparer les résultats avant et après les corrections.

## Environnement technique

Le projet s'appuie sur les outils suivants :

- VirtualBox pour la gestion des machines virtuelles.
- Debian 12 pour les serveurs et la machine Greenbone.
- Greenbone (OpenVAS) pour détecter les vulnérabilités.
- Metasploitable 2 comme machine de test volontairement vulnérable.
- Python 3.12 pour l'analyse des rapports CSV.
- Git et GitHub pour le suivi du projet.
- Visual Studio Code pour la rédaction et le développement.

Les machines seront installées sur un réseau de test isolé afin de réaliser les scans dans un environnement contrôlé.

## Déroulement du projet

Le travail est organisé en trois missions :

**1. Réalisation du scan**

Installation de Greenbone, préparation des machines virtuelles et réalisation d'un premier scan de vulnérabilités.

**2. Analyse et priorisation**

Analyse des rapports obtenus, classement des vulnérabilités et création d'une liste des dix failles à corriger en priorité.

**3. Correction et vérification**

Mise en place des corrections, réalisation d'un second scan et comparaison des résultats pour vérifier les améliorations.

## Organisation du dépôt

- `docs/` : documentation et rapports d'analyse.
- `rapports/` : résultats des scans au format PDF et CSV.
- `scripts/` : scripts Python utilisés pour analyser et comparer les résultats.

## État d'avancement

Projet en cours de préparation.

Les différentes étapes et les résultats seront ajoutés au fur et à mesure de la réalisation du projet.
