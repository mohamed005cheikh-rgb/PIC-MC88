<div align="center">

# 📸 PIC by MC88

**Un studio photo, dans votre navigateur.**

</div>

---

## 👋 Bienvenue

PIC est un petit studio photo qui tient dans une seule page web.

Vous y déposez une image, et vous la travaillez comme vous le feriez dans un vrai laboratoire : luminosité, contraste, netteté, couleurs — tout se règle au curseur, en direct, sous vos yeux. Vous pouvez aussi piocher parmi **cent filtres** classés par ambiance, réparer une vieille photo abîmée, ou confier à l'IA le soin de la coloriser ou de l'agrandir.

Tout ce qui se passe localement — réglages, filtres, export — reste **sur votre appareil**. Rien ne part ailleurs. Seules les trois actions IA envoient votre photo à un service public (Hugging Face), et c'est clairement annoncé avant chaque utilisation.

C'est un outil pour prendre son temps, essayer, annuler, recommencer — jusqu'à ce que l'image ressemble enfin à ce qu'on avait en tête.

---

## 📸 Un aperçu

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/pic-mc88/raw/main/images/Sc1.png" alt="Studio d'amélioration avec curseurs" width="100%" />
</div>

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/pic-mc88/raw/main/images/Sc2.png" alt="Bibliothèque de filtres" width="100%" />
</div>

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/pic-mc88/raw/main/images/Sr1.gif" alt="Ajuster une photo en temps réel" width="100%" />
</div>

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/pic-mc88/raw/main/images/Sr2.gif" alt="Restaurer une photo ancienne avec l'IA" width="100%" />
</div>

---

## ✨ Ce que vous trouverez

**Sept curseurs pour tout régler.**  
Luminosité, contraste, netteté, réduction de bruit, saturation, défloutage, intensité globale. Chaque ajustement s'applique immédiatement — vous voyez la photo changer à chaque mouvement.

**Cent filtres, classés par humeur.**  
Des filtres naturels (*Raw*), des corrections de couleur (*Color*), des ambiances (*Mood*), du noir et blanc (*B&W*), des outils de réparation (*Repair*), des effets artistiques (*Art*), et une catégorie d'expérimentations (*Chaos*). Vous cherchez par nom, vous filtrez par catégorie, et si l'inspiration manque, un bouton **Surprise** (🎲) en choisit un pour vous.

**Un studio IA pour les cas difficiles.**  
Trois actions sont là pour vous aider :
- **Colorize** — redonner vie à une photo en noir et blanc.
- **Restore** — réparer les rayures, le bruit, les visages flous.
- **Enhance & Upscale** — améliorer les détails et augmenter la résolution.

Ces trois actions **envoient votre photo à un modèle public Hugging Face**. Tout le reste (curseurs, filtres, export) fonctionne à 100% sur votre machine.

**Annuler, refaire — autant de fois qu'il faut.**  
Trente étapes d'historique couvrent vos réglages et vos filtres. `Ctrl+Z` pour revenir en arrière, `Ctrl+Y` pour avancer. Vous pouvez essayer sans crainte.

**Vos propres préréglages.**  
Vous avez trouvé une combinaison qui vous plaît ? Sauvegardez-la sous un nom — elle reviendra en un clic la prochaine fois. Jusqu'à vingt réglages personnels.

**Un assistant qui vous comprend.**  
Au lieu de tourner les curseurs à l'aveugle, dites simplement *« too dark »*, *« still blurry »* ou *« colors feel off »*. L'assistant ajuste les paramètres tout seul. Vous pouvez aussi décrire votre ressenti librement — il repère les mots-clés et agit.

**Comparer avant / après.**  
Un bouton suffit pour faire glisser une ligne de comparaison sur l'image. Utile pour mesurer le chemin parcouru — à la souris comme au doigt.

**Exporter comme vous voulez.**  
JPEG, PNG ou WebP, avec un réglage de qualité pour les formats compressés. Un raccourci `Ctrl+S` pour télécharger directement.

---

## 🧭 Comment ça marche

**1. Déposez votre photo.**  
Cliquez sur la zone d'import ou glissez-déposez votre image. Jusqu'à 15 Mo — ce qui couvre largement la plupart des photos de téléphone.

**2. Réglez ce qui doit l'être.**  
Dans l'onglet *Adjust*, les sept curseurs font le gros du travail. Chaque mouvement est appliqué en direct.

**3. Choisissez un filtre.**  
Dans l'onglet *Filters*, parcourez les cent préréglages. Cherchez par nom, filtrez par catégorie, essayez, annulez, réessayez. Le bouton *Surprise* peut vous sortir de votre zone de confort.

**4. Si besoin, passez par l'IA.**  
Dans *AI Studio*, choisissez une action. Le traitement prend une dizaine de secondes, et le résultat devient une nouvelle version de votre image — que vous pouvez comparer à l'originale et continuer à travailler.

**5. Exportez.**  
Dans *Export*, choisissez le format et la qualité, puis téléchargez. Le fichier final reste chez vous.

À chaque étape, vous pouvez annuler. Rien n'est définitif tant que vous n'avez pas cliqué sur « télécharger ».

---

## 🛠️ Petits coups de main

**Votre image refuse de se charger ?**  
Vérifiez qu'elle ne dépasse pas 15 Mo, et qu'elle est dans un format courant (JPEG, PNG, WebP). Si le problème persiste, essayez-en une autre — parfois c'est le fichier lui-même qui est abîmé.

**Les actions IA ne répondent pas ?**  
Les modèles publics Hugging Face sont parfois surchargés. Vérifiez votre connexion, attendez une minute, réessayez. Un repli local s'active automatiquement : pour *Restore* et *Upscale*, les curseurs compensent ; pour *Colorize*, aucune solution locale honnête n'existe, et l'outil vous le dira clairement.

**Tout est lent ?**  
Sur une grosse image ou un appareil modeste, c'est normal. L'outil réduit automatiquement la taille de travail — 1536 px pour l'IA, 1080 px pour l'aperçu. Fermez quelques onglets si votre machine peine.

**Vos préréglages ont disparu ?**  
Vous êtes probablement en navigation privée, où le stockage local est désactivé. Utilisez une fenêtre normale pour les conserver.

**L'assistant ne comprend pas ?**  
Soyez plus précis : *« too dark »* plutôt que *« bad »*. Il reconnaît les mots comme *dark*, *bright*, *blurry*, *noise*, *color*, *detail*. Les suggestions rapides proposées à côté du champ sont toujours un bon point de départ.

---

<div align="center">

### 📞 Une question, une idée ?

[![Email](https://img.shields.io/badge/Email-mohamed005cheikh@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamed005cheikh@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+222_30_72_64_75-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/22230726475)

<br />

*Bonnes retouches.*

<sub>© 2026 Mohamed Cheikh — MC88</sub>

</div>
