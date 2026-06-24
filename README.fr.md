<!-- markdownlint-disable MD013 -->
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11%2B-blue)](https://www.python.org/)
[![Markdown lint](https://img.shields.io/badge/Markdown-lint%20friendly-brightgreen)](https://github.com/DavidAnson/markdownlint)
[![CI](https://github.com/valorisa/advanced-multi-agent-orchestrator/actions/workflows/markdownlint.yml/badge.svg)](https://github.com/valorisa/advanced-multi-agent-orchestrator/actions/workflows/markdownlint.yml)

# Advanced Multi Agent Orchestrator

Advanced Multi Agent Orchestrator est un projet de démarrage destiné à apprendre comment
sont structurés, documentés et maintenus les systèmes d'IA multi-agents.

Le projet a été conçu pour être clair, lisible et professionnel. Son but est de t'aider à
comprendre comment un petit contrôleur peut coordonner plusieurs agents spécialisés afin
de résoudre une tâche étape par étape.

## À quoi sert ce projet

Ce projet t'aide à comprendre les bases de l'orchestration multi-agents :

- Découper une tâche complexe en sous-tâches.
- Confier chaque sous-tâche à un agent spécialisé.
- Vérifier la qualité du résultat final.
- Garder un workflow compréhensible et maintenable.

En termes simples, ce projet montre comment un orchestrateur agit comme un chef d'orchestre.
Il ne fait pas tout seul. Il délègue, vérifie et combine les résultats.

## Pour qui est ce projet

Ce dépôt s'adresse à :

- Des débutants qui veulent découvrir les agents IA sans difficulté.
- Des développeurs qui veulent une base propre pour démarrer.
- Des équipes qui ont besoin d'un socle documenté pour expérimenter.

Aucune connaissance avancée n'est nécessaire. Si tu sais lire du Markdown, modifier du YAML
et lancer quelques commandes Python, tu peux déjà utiliser ce projet.

## Organisation du dépôt

Le dépôt est organisé pour rester simple à comprendre :

- README.md — documentation principale en anglais.
- README.fr.md — version française (ce fichier).
- pyproject.toml — métadonnées Python.
- .markdownlint.yml — règles Markdown.
- .github/workflows/markdownlint.yml — contrôle automatique via GitHub Actions.

## Philosophie du projet

Ce projet suit trois principes :

- **Clarté** — chaque élément doit être facile à comprendre.
- **Simplicité** — on commence petit avant d'ajouter de la complexité.
- **Extensibilité** — la structure permet de passer ensuite à des agents plus avancés.

## Installation

### Prérequis

Il faut :

- Python 3.11 ou plus récent.
- Git.
- GitHub CLI (gh).

### Cloner le dépôt

```bash
git clone https://github.com/valorisa/advanced-multi-agent-orchestrator.git
cd advanced-multi-agent-orchestrator
```

### Créer un environnement virtuel

```bash
python -m venv .venv
```

### Activer l'environnement dans PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

### Installer les dépendances

```bash
python -m pip install --upgrade pip
```

## Prochaine étape

Une fois l'installation terminée, exécute la commande suivante pour vérifier ton environnement et recevoir ta première mission :

```bash
orchestrator-kata
```

Cette commande n'invoque aucun agent IA. C'est un **point de contrôle pédagogique** conçu pour te rediriger vers le vrai sujet de ce dépôt : la gouvernance open-source, la documentation et la maintenabilité.

Si tu t'attendais à un orchestrateur exécutable, ce dépôt n'est pas ce que tu crois. Lis la mission ci-dessus, et décide si tu restes.

## Utilisation

Un flux minimal ressemble souvent à ceci :

1. L'utilisateur pose une question.
2. Le contrôleur analyse la demande.
3. Le contrôleur choisit un agent.
4. L'agent produit un résultat.
5. Un vérificateur contrôle la sortie.
6. La réponse finale est assemblée.

Cette structure est utile pour l'assistance au code, la recherche, la documentation
et les workflows d'automatisation.

## Fichiers de documentation

- CONTRIBUTING.md — comment contribuer.
- CODE_OF_CONDUCT.md — comportement attendu.
- SECURITY.md — comment signaler une vulnérabilité.
- SUPPORT.md — comment obtenir de l'aide.
- CHANGELOG.md — évolution du projet.

## Commandes Git et GitHub CLI

```bash
git init
gh auth status || gh auth login
git add .
git commit -m "chore: initial commit"
git branch -M main
gh repo create advanced-multi-agent-orchestrator --public --source=. --remote=origin --push
```

## Licence

Ce projet est distribué sous licence MIT. Voir [LICENSE](LICENSE) pour les détails.

## Version anglaise

La version anglaise complète est disponible dans [README.md](README.md).
