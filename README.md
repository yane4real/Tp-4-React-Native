# TP 4 – React Native Navigation (Expo)

## 📌 Description

Ce projet est une application **React Native** développée avec **Expo**, réalisée dans le cadre du **TP 4**. Elle met en œuvre la **navigation par onglets (Bottom Tabs)** et la **navigation par pile (Stack Navigator)** à l’aide de **React Navigation**.

L’application est compatible avec **Expo Go** et respecte une structure claire avec des écrans séparés.

---

## 🎯 Objectifs pédagogiques

* Comprendre la navigation avec React Navigation
* Utiliser un **Stack Navigator** et un **Tab Navigator**
* Structurer un projet React Native
* Personnaliser les onglets et le header
* Ajouter une AppBar personnalisée
* Gérer les zones sûres avec **SafeAreaView**

---

## 🧱 Structure du projet

```
MonApp/
│── App.js
│── screens/
│   ├── HomeScreen.js
│   ├── DetailsScreen.js
│   ├── SettingsScreen.js
│   └── AppBar.js
```

---

## ⚙️ Technologies utilisées

* React Native
* Expo
* React Navigation
* JavaScript (ES6)

---

## 📦 Installation

1. Installer les dépendances :

```bash
npm install
```

2. Installer React Navigation :

```bash
npm install @react-navigation/native
npm install @react-navigation/native-stack
npm install @react-navigation/bottom-tabs
expo install react-native-screens react-native-safe-area-context
```

---

## ▶️ Lancer l’application

```bash
npm start
```

* Scanner le QR code avec l’application **Expo Go**

---

## 🧭 Fonctionnalités

* Navigation par onglets :

  * 🏠 Maison
  * ⚙️ Paramètres
* Navigation par pile dans l’onglet Maison
* Passage de paramètres entre écrans
* AppBar personnalisée
* Interface adaptée aux zones sécurisées

---

## 📱 Résultat attendu

* L’onglet **Maison** affiche l’écran d’accueil avec un bouton vers les détails
* L’onglet **Paramètres** affiche l’écran des paramètres
* La navigation fonctionne correctement dans **Expo Go**

---

## 👨‍🎓 Réalisé par

* Nom : Anouar
* Module : React Native
* TP : TP 4 – Navigation

---

✅ Projet conforme aux exigences du **TP 4 React Native**.
