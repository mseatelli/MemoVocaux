# 🎙️ Mémos Vocaux

Application web pour enregistrer des mémos vocaux avec transcription automatique et export PDF/Word.

## ✨ Fonctionnalités

- 🎤 **Enregistrement vocal** avec contrôle start/stop
- 🗣️ **Transcription automatique** en temps réel (reconnaissance vocale)
- ⏱️ **Timer** pour suivre la durée d'enregistrement
- 💾 **Sauvegarde locale** de tous vos mémos
- 📄 **Export PDF** avec mise en page professionnelle
- 📝 **Export Word** (.doc) pour édition
- 🎨 **Interface moderne** et intuitive
- 🔒 **100% privé** - vos données restent sur votre appareil

## 🚀 Démarrage rapide

### Installation

Aucune installation nécessaire ! Il suffit de télécharger et d'ouvrir le fichier HTML.

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/memos-vocaux.git

# Ouvrir le fichier
cd memos-vocaux
# Double-cliquez sur index.html ou ouvrez-le dans votre navigateur
```

### Utilisation

1. **Démarrer un enregistrement** : Cliquez sur le bouton 🎤
2. **Parler** : La transcription apparaît automatiquement
3. **Arrêter** : Cliquez sur le bouton ⏹️
4. **Sauvegarder** : Donnez un titre et cliquez sur "Sauvegarder"
5. **Exporter** : Téléchargez en PDF ou Word depuis la liste des mémos

## 📋 Prérequis

- Navigateur moderne (Chrome, Firefox, Edge, Safari)
- Connexion Internet (pour charger jsPDF)
- Microphone fonctionnel
- Autorisation d'accès au microphone

## 🛠️ Technologies utilisées

- **HTML5** - Structure
- **CSS3** - Design moderne avec animations
- **JavaScript Vanilla** - Logique applicative
- **Web Speech API** - Reconnaissance vocale
- **MediaRecorder API** - Enregistrement audio
- **LocalStorage API** - Sauvegarde des données
- **jsPDF** - Génération de PDF

## 📱 Compatibilité

| Navigateur | Support reconnaissance vocale | Support enregistrement |
|------------|-------------------------------|------------------------|
| Chrome     | ✅ Complet                    | ✅                     |
| Edge       | ✅ Complet                    | ✅                     |
| Safari     | ⚠️ Partiel                    | ✅                     |
| Firefox    | ❌ Non supporté               | ✅                     |

> **Note** : La reconnaissance vocale fonctionne mieux sur Chrome et Edge. Sur les autres navigateurs, vous pouvez toujours enregistrer et taper manuellement.

## 🎨 Captures d'écran

### Interface principale
```
┌─────────────────────────────────────┐
│         🎙️ Mémos Vocaux            │
├─────────────────────────────────────┤
│          ┌─────────┐                │
│          │ 00:00   │                │
│          └─────────┘                │
│             🎤                       │
│    🔴 Enregistrement en cours...    │
├─────────────────────────────────────┤
│  Titre du mémo                      │
│  ┌───────────────────────────────┐  │
│  │ Réunion client                │  │
│  └───────────────────────────────┘  │
│                                     │
│  Contenu (transcription)            │
│  ┌───────────────────────────────┐  │
│  │ Discussion sur le projet...   │  │
│  │                               │  │
│  └───────────────────────────────┘  │
│                                     │
│  [💾 Sauvegarder]  [🗑️ Effacer]    │
└─────────────────────────────────────┘
```

## 📂 Structure du projet

```
memos-vocaux/
│
├── index.html          # Application complète (fichier unique)
├── README.md           # Ce fichier
└── LICENSE             # Licence MIT
```

## 🔧 Configuration

Aucune configuration requise ! L'application fonctionne immédiatement.

### Personnalisation (optionnel)

Pour personnaliser les couleurs, modifiez les variables CSS dans le `<style>` :

```css
/* Gradient de fond */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Couleur primaire */
.btn-primary {
    background: #667eea;
}
```

## 💡 Cas d'usage

- 📝 Notes de réunion
- 🎓 Mémos d'étude
- 💼 Idées de projet
- 📋 Liste de tâches vocales
- 🎤 Interviews et entretiens
- 📚 Résumés de lecture

## 🔒 Confidentialité et sécurité

- ✅ **Aucune donnée n'est envoyée sur Internet**
- ✅ Tous les mémos sont stockés localement dans votre navigateur
- ✅ Aucun serveur externe n'est utilisé
- ✅ Aucun compte utilisateur requis
- ✅ Pas de tracking ou d'analytics

## 🐛 Résolution de problèmes

### Le microphone ne fonctionne pas
- Vérifiez que vous avez autorisé l'accès au microphone
- Sur Chrome : cliquez sur l'icône 🔒 dans la barre d'adresse
- Assurez-vous qu'aucune autre application n'utilise le micro

### La transcription ne fonctionne pas
- Utilisez Chrome ou Edge pour de meilleurs résultats
- Vérifiez votre connexion Internet
- Parlez clairement et distinctement
- Assurez-vous que la langue est bien configurée (fr-FR)

### Les mémos disparaissent
- Ne videz pas le cache de votre navigateur
- Ne naviguez pas en mode privé/incognito
- Exportez régulièrement vos mémos importants en PDF/Word

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/amelioration`)
3. Commit vos changements (`git commit -m 'Ajout d'une fonctionnalité'`)
4. Push vers la branche (`git push origin feature/amelioration`)
5. Ouvrir une Pull Request

## 📝 Roadmap

- [ ] Support multilingue (EN, ES, DE)
- [ ] Mode sombre
- [ ] Export en format Markdown
- [ ] Catégories de mémos
- [ ] Recherche dans les mémos
- [ ] Synchronisation cloud (optionnelle)
- [ ] Application mobile (PWA)
- [ ] Édition des mémos existants

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Auteur

Créé par [Marc Seatelli](https://github.com/mseatelli)

## 🙏 Remerciements

- [jsPDF](https://github.com/parallax/jsPDF) - Génération de PDF
- [Web Speech API](https://developer.mozilla.org/fr/docs/Web/API/Web_Speech_API) - Reconnaissance vocale
- La communauté open source

## 📞 Support

Pour toute question ou problème :
- Ouvrez une [issue](https://github.com/mseatelli/memos-vocaux/issues)
- Contactez-moi sur (mailto:marcseatelli@orange.fr)

---

⭐ **Si vous aimez ce projet, n'hésitez pas à lui donner une étoile !**

Made with ☕ and 💻
