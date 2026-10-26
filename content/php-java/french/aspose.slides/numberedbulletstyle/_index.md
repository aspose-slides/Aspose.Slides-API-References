---
title: NumberedBulletStyle
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/numberedbulletstyle/
---
## NumberedBulletStyle classe

Représente le style des puces numérotées.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[NotDefined](#NotDefined) | -1 | Non défini. |
[BulletAlphaLCPeriod](#BulletAlphaLCPeriod) | 0 | Caractères alphabétiques minuscules avec un point. Exemple : a., b., c., ... |
[BulletAlphaUCPeriod](#BulletAlphaUCPeriod) | 1 | Caractères alphabétiques majuscules avec un point. Exemple : A., B., C., ... |
[BulletArabicParenRight](#BulletArabicParenRight) | 2 | Chiffres arabes avec parenthèse fermante. Exemple : 1), 2), 3), ... |
[BulletArabicPeriod](#BulletArabicPeriod) | 3 | Chiffres arabes avec un point. Exemple : 1., 2., 3., ... |
[BulletRomanLCParenBoth](#BulletRomanLCParenBoth) | 4 | Chiffres romains minuscules avec deux parenthèses. Exemple : (i), (ii), (iii), ... |
[BulletRomanLCParenRight](#BulletRomanLCParenRight) | 5 | Chiffres romains minuscules avec parenthèse fermante. Exemple : i), ii), iii), ... |
[BulletRomanLCPeriod](#BulletRomanLCPeriod) | 6 | Chiffres romains minuscules avec un point. Exemple : i., ii., iii., ... |
[BulletRomanUCPeriod](#BulletRomanUCPeriod) | 7 | Chiffres romains majuscules avec un point. Exemple : I., II., III., ... |
[BulletAlphaLCParenBoth](#BulletAlphaLCParenBoth) | 8 | Caractères alphabétiques minuscules avec deux parenthèses. Exemple : (a), (b), (c), ... |
[BulletAlphaLCParenRight](#BulletAlphaLCParenRight) | 9 | Caractères alphabétiques minuscules avec parenthèse fermante. Exemple : a), b), c), ... |
[BulletAlphaUCParenBoth](#BulletAlphaUCParenBoth) | 10 | Caractères alphabétiques majuscules avec deux parenthèses. Exemple : (A), (B), (C), ... |
[BulletAlphaUCParenRight](#BulletAlphaUCParenRight) | 11 | Caractères alphabétiques majuscules avec parenthèse fermante. Exemple : A), B), C), ... |
[BulletArabicParenBoth](#BulletArabicParenBoth) | 12 | Chiffres arabes avec deux parenthèses. Exemple : (1), (2), (3), ... |
[BulletArabicPlain](#BulletArabicPlain) | 13 | Chiffres arabes. Exemple : 1, 2, 3, ... |
[BulletRomanUCParenBoth](#BulletRomanUCParenBoth) | 14 | Chiffres romains majuscules avec deux parenthèses. Exemple : (I), (II), (III), ... |
[BulletRomanUCParenRight](#BulletRomanUCParenRight) | 15 | Chiffres romains majuscules avec parenthèse fermante. Exemple : I), II), III), ... |
[BulletSimpChinPlain](#BulletSimpChinPlain) | 16 | Chinois simplifié sans point. |
[BulletSimpChinPeriod](#BulletSimpChinPeriod) | 17 | Chinois simplifié avec point. |
[BulletCircleNumDBPlain](#BulletCircleNumDBPlain) | 18 | Numéro encerclé double octet pour les valeurs jusqu’à 10, à partir de 11 – chiffres arabes. |
[BulletCircleNumWDWhitePlain](#BulletCircleNumWDWhitePlain) | 19 | Numéro coloré en texte avec un cercle de même couleur autour (numéros cercle blanc Wingdings). À partir de 11 – chiffres arabes. |
[BulletCircleNumWDBlackPlain](#BulletCircleNumWDBlackPlain) | 20 | Numéro de couleur d’ombre avec arrière-plan circulaire de la couleur de texte normale (numéros cercle noir Wingdings). |
[BulletTradChinPlain](#BulletTradChinPlain) | 21 | Chinois traditionnel sans point. |
[BulletTradChinPeriod](#BulletTradChinPeriod) | 22 | Chinois traditionnel avec point. |
[BulletArabicAlphaDash](#BulletArabicAlphaDash) | 23 | Caractères alphabétiques de la langue arabe avec un tiret. |
[BulletArabicAbjadDash](#BulletArabicAbjadDash) | 24 | Alphabet Abjad arabe avec un tiret. |
[BulletHebrewAlphaDash](#BulletHebrewAlphaDash) | 25 | Caractères alphabétiques de la langue hébraïque avec un tiret. |
[BulletKanjiKoreanPlain](#BulletKanjiKoreanPlain) | 26 | Nombres japonais/coréens sans point. |
[BulletKanjiKoreanPeriod](#BulletKanjiKoreanPeriod) | 27 | Nombres japonais/coréens avec point. |
[BulletArabicDBPlain](#BulletArabicDBPlain) | 28 | Système de numérotation arabe double octet (sans ponctuation). |
[BulletArabicDBPeriod](#BulletArabicDBPeriod) | 29 | Système de numérotation arabe double octet avec point double octet. |
[BulletThaiAlphaPeriod](#BulletThaiAlphaPeriod) | 30 | Alphabet thaï avec point. |
[BulletThaiAlphaParenRight](#BulletThaiAlphaParenRight) | 31 | Parenthèses de l’alphabet thaï – droite. |
[BulletThaiAlphaParenBoth](#BulletThaiAlphaParenBoth) | 32 | Parenthèses de l’alphabet thaï – les deux. |
[BulletThaiNumPeriod](#BulletThaiNumPeriod) | 33 | Point numérique thaï. |
[BulletThaiNumParenRight](#BulletThaiNumParenRight) | 34 | Parenthèses numériques thaï – droite. |
[BulletThaiNumParenBoth](#BulletThaiNumParenBoth) | 35 | Parenthèses numériques thaï – les deux. |
[BulletHindiAlphaPeriod](#BulletHindiAlphaPeriod) | 36 | Alphabet hindi avec point – voyelles. |
[BulletHindiNumPeriod](#BulletHindiNumPeriod) | 37 | Point numérique hindi. |
[BulletKanjiSimpChinDBPeriod](#BulletKanjiSimpChinDBPeriod) | 38 | Kanji Chinois simple DBPeriod. |
[BulletHindiNumParenRight](#BulletHindiNumParenRight) | 39 | Parenthèses numériques hindi – droite. |
[BulletHindiAlpha1Period](#BulletHindiAlpha1Period) | 40 | Alphabet hindi avec point – consonnes. |


---


### NotDefined {#NotDefined}
Non défini.

---

### BulletAlphaLCPeriod {#BulletAlphaLCPeriod}
Caractères alphabétiques minuscules avec un point. Exemple : a., b., c., ...

---

### BulletAlphaUCPeriod {#BulletAlphaUCPeriod}
Caractères alphabétiques majuscules avec un point. Exemple : A., B., C., ...

---

### BulletArabicParenRight {#BulletArabicParenRight}
Chiffres arabes avec parenthèse fermante. Exemple : 1), 2), 3), ...

---

### BulletArabicPeriod {#BulletArabicPeriod}
Chiffres arabes avec un point. Exemple : 1., 2., 3., ...

---

### BulletRomanLCParenBoth {#BulletRomanLCParenBoth}
Chiffres romains minuscules avec deux parenthèses. Exemple : (i), (ii), (iii), ...

---

### BulletRomanLCParenRight {#BulletRomanLCParenRight}
Chiffres romains minuscules avec parenthèse fermante. Exemple : i), ii), iii), ...

---

### BulletRomanLCPeriod {#BulletRomanLCPeriod}
Chiffres romains minuscules avec un point. Exemple : i., ii., iii., ...

---

### BulletRomanUCPeriod {#BulletRomanUCPeriod}
Chiffres romains majuscules avec un point. Exemple : I., II., III., ...

---

### BulletAlphaLCParenBoth {#BulletAlphaLCParenBoth}
Caractères alphabétiques minuscules avec deux parenthèses. Exemple : (a), (b), (c), ...

---

### BulletAlphaLCParenRight {#BulletAlphaLCParenRight}
Caractères alphabétiques minuscules avec parenthèse fermante. Exemple : a), b), c), ...

---

### BulletAlphaUCParenBoth {#BulletAlphaUCParenBoth}
Caractères alphabétiques majuscules avec deux parenthèses. Exemple : (A), (B), (C), ...

---

### BulletAlphaUCParenRight {#BulletAlphaUCParenRight}
Caractères alphabétiques majuscules avec parenthèse fermante. Exemple : A), B), C), ...

---

### BulletArabicParenBoth {#BulletArabicParenBoth}
Chiffres arabes avec deux parenthèses. Exemple : (1), (2), (3), ...

---

### BulletArabicPlain {#BulletArabicPlain}
Chiffres arabes. Exemple : 1, 2, 3, ...

---

### BulletRomanUCParenBoth {#BulletRomanUCParenBoth}
Chiffres romains majuscules avec deux parenthèses. Exemple : (I), (II), (III), ...

---

### BulletRomanUCParenRight {#BulletRomanUCParenRight}
Chiffres romains majuscules avec parenthèse fermante. Exemple : I), II), III), ...

---

### BulletSimpChinPlain {#BulletSimpChinPlain}
Chinois simplifié sans point.

---

### BulletSimpChinPeriod {#BulletSimpChinPeriod}
Chinois simplifié avec point.

---

### BulletCircleNumDBPlain {#BulletCircleNumDBPlain}
Numéro encerclé double octet pour les valeurs jusqu’à 10, à partir de 11 – chiffres arabes.

---

### BulletCircleNumWDWhitePlain {#BulletCircleNumWDWhitePlain}
Numéro coloré en texte avec un cercle de même couleur autour (numéros cercle blanc Wingdings). À partir de 11 – chiffres arabes.

---

### BulletCircleNumWDBlackPlain {#BulletCircleNumWDBlackPlain}
Numéro de couleur d’ombre avec arrière-plan circulaire de la couleur de texte normale (numéros cercle noir Wingdings).

---

### BulletTradChinPlain {#BulletTradChinPlain}
Chinois traditionnel sans point.

---

### BulletTradChinPeriod {#BulletTradChinPeriod}
Chinois traditionnel avec point.

---

### BulletArabicAlphaDash {#BulletArabicAlphaDash}
Caractères alphabétiques de la langue arabe avec un tiret.

---

### BulletArabicAbjadDash {#BulletArabicAbjadDash}
Alphabet Abjad arabe avec un tiret.

---

### BulletHebrewAlphaDash {#BulletHebrewAlphaDash}
Caractères alphabétiques de la langue hébraïque avec un tiret.

---

### BulletKanjiKoreanPlain {#BulletKanjiKoreanPlain}
Nombres japonais/coréens sans point.

---

### BulletKanjiKoreanPeriod {#BulletKanjiKoreanPeriod}
Nombres japonais/coréens avec point.

---

### BulletArabicDBPlain {#BulletArabicDBPlain}
Système de numérotation arabe double octet (sans ponctuation).

---

### BulletArabicDBPeriod {#BulletArabicDBPeriod}
Système de numérotation arabe double octet avec point double octet.

---

### BulletThaiAlphaPeriod {#BulletThaiAlphaPeriod}
Alphabet thaï avec point.

---

### BulletThaiAlphaParenRight {#BulletThaiAlphaParenRight}
Parenthèses de l’alphabet thaï – droite.

---

### BulletThaiAlphaParenBoth {#BulletThaiAlphaParenBoth}
Parenthèses de l’alphabet thaï – les deux.

---

### BulletThaiNumPeriod {#BulletThaiNumPeriod}
Point numérique thaï.

---

### BulletThaiNumParenRight {#BulletThaiNumParenRight}
Parenthèses numériques thaï – droite.

---

### BulletThaiNumParenBoth {#BulletThaiNumParenBoth}
Parenthèses numériques thaï – les deux.

---

### BulletHindiAlphaPeriod {#BulletHindiAlphaPeriod}
Alphabet hindi avec point – voyelles.

---

### BulletHindiNumPeriod {#BulletHindiNumPeriod}
Point numérique hindi.

---

### BulletKanjiSimpChinDBPeriod {#BulletKanjiSimpChinDBPeriod}
Kanji Chinois simple DBPeriod.

---

### BulletHindiNumParenRight {#BulletHindiNumParenRight}
Parenthèses numériques hindi – droite.

---

### BulletHindiAlpha1Period {#BulletHindiAlpha1Period}
Alphabet hindi avec point – consonnes.