# Projet A — AI Administrative Assistant

**Agent IA coordinateur administratif développé avec n8n.**

Projet A est un assistant intelligent accessible via Telegram, conçu pour automatiser et simplifier les tâches administratives grâce à l'intelligence artificielle et à l'intégration de services externes.

## Fonctionnalités principales

- **Gestion d'agenda :** consultation, création, modification et suppression de rendez-vous avec Google Calendar.
- **Gestion des emails :** consultation, analyse des priorités et préparation de brouillons avec Gmail.
- **Gestion documentaire :** recherche et analyse de documents avec Google Drive.
- **Génération de rapports :** création de documents structurés avec Google Docs.
- **Recherche Web :** recherche d'informations avec SerpApi.
- **Briefing quotidien :** synthèse automatique des rendez-vous, emails et priorités de la journée.

## Technologies

- n8n — Orchestration et automatisation
- Docker — Environnement d'exécution
- Telegram Bot API — Interface utilisateur
- Modèles de langage (LLM) — Intelligence artificielle
- Google Calendar, Gmail, Drive et Docs — Services Google
- SerpApi — Recherche Web

## Architecture

Telegram → Vérification utilisateur → Agent IA coordinateur → Outils spécialisés → Réponse Telegram.

Un second agent IA assure la préparation du briefing quotidien.

## Sécurité

- Vérification des utilisateurs autorisés.
- Confirmation humaine avant les actions sensibles.
- Validation avant l'envoi des emails.
- Gestion sécurisée des identifiants et des accès.

## Installation

1. Installer Docker et déployer n8n.
2. Configurer les connexions aux services nécessaires.
3. Importer le workflow JSON.
4. Configurer les identifiants dans n8n.
5. Tester et activer le workflow.

## Auteur

**Russel Pere**  
Étudiant ingénieur — ESIGELEC

*Projet personnel — Intelligence artificielle, automatisation et intégration de services.*


