# Signature e-mail ecobulles — Marine PERNET

Signature HTML dynamique (liens cliquables : site web, Facebook, Instagram, LinkedIn, YouTube, tous les téléphones), fidèle à la maquette « Marine V2 ».

## Fichiers

| Fichier | Usage |
|---|---|
| `signature-marine.html` | **Autonome** : les 12 images sont intégrées en base64 (~180 Ko). Fonctionne partout sans hébergement. |
| `signature-marine-hosted.html` | **Léger** (< 5 Ko) : les images sont servies depuis GitHub Pages. À utiliser **après** avoir activé GitHub Pages (voir ci-dessous). |
| `assets/` | Les 12 images utilisées par la version légère. |

## Activer GitHub Pages (pour la version légère)

1. Sur ce dépôt : **Settings → Pages**.
2. **Source** : « Deploy from a branch », puis **Branch : `main` / `/ (root)`** → **Save**.
3. Attendre ~1 minute : les images seront accessibles sur
   `https://mpernet.github.io/signature-mail/assets/…`

## Installer la signature — Gmail

1. Ouvrir le fichier HTML dans un navigateur (double-clic).
2. Tout sélectionner (**Ctrl/Cmd + A**) puis copier (**Ctrl/Cmd + C**).
3. Gmail → ⚙️ **Voir tous les paramètres** → onglet **Général** → section **Signature**.
4. Coller la signature dans l'éditeur → **Enregistrer les modifications** en bas.
   > Avec la version légère, Gmail affichera un message « les images ne s'affichent pas » : cliquer sur l'avertissement pour autoriser/charger les images distantes.

## Installer la signature — Outlook (bureau Windows)

1. Ouvrir le fichier HTML dans un navigateur, tout sélectionner et copier.
2. Outlook → **Fichier → Options → Courrier → Signatures… → Nouvelle** (nommer « ecobulles »).
3. Coller la signature → **OK**.

## Installer la signature — Apple Mail

1. **Mail → Réglages → Signatures**, créer une signature vide.
2. Ouvrir le fichier HTML dans Safari, tout sélectionner et copier, puis coller dans la zone de signature.

## Personnalisation

- Modifier les textes/URL directement dans le fichier HTML (vos n° sont en `tel:+33…`, le site en `https://www.ecobulles.com`, les 4 icônes en haut de la ligne 2).
- Un emplacement vide existait dans la maquette au pointillez de la ligne d'adresse (probablement votre e-mail) : pour l'ajouter, dupliquer le bloc `<a href="https://www.ecobulles.com">…</a>` sur la ligne 3.
