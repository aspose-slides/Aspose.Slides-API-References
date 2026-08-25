---
title: EmbeddingLevel
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/embeddinglevel/
---
## EmbeddingLevel classe

 Représente les droits de licence pour l'intégration de la police.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[Installable](#Installable) | 0 | Les polices avec ce paramètre indiquent qu'elles peuvent être intégrées et installées de façon permanente sur le système distant par une application. L'utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l'acheteur original, et est soumis au même contrat de licence utilisateur final, droit d'auteur, brevet de design et/ou marque que l'acheteur original. |
[Restricted](#Restricted) | 2 | Les polices qui n'ont que ce bit défini ne doivent pas être modifiées, intégrées ou échangées de quelque manière que ce soit sans obtenir d'abord la permission du propriétaire légal. |
[PreviewPrint](#PreviewPrint) | 4 | Lorsque ce bit est défini, la police peut être intégrée et chargée temporairement sur le système distant. Les documents contenant des polices Preview &amp; Print doivent être ouverts en « lecture seule » ; aucune modification ne peut être appliquée au document. |
[Editable](#Editable) | 8 | Lorsque ce bit est défini, la police peut être intégrée mais ne doit être installée que temporairement sur d'autres systèmes. Contrairement aux polices Preview &amp; Print, les documents contenant des polices Editable peuvent être ouverts en lecture, la modification est autorisée et les changements peuvent être enregistrés. |
[NoSubsetting](#NoSubsetting) | 256 | Lorsque ce bit est défini, la police ne peut pas être sous-ensemble avant l'intégration. D'autres restrictions d'intégration spécifiées dans les bits 0-3 et 9 s'appliquent également. |
[BitmapOnly](#BitmapOnly) | 512 | Lorsque ce bit est défini, seules les bitmaps contenues dans la police peuvent être intégrées. Aucune donnée de contour ne peut être intégrée. S'il n'y a aucune bitmap disponible dans la police, alors la police est considérée comme non intégrable et les services d'intégration échoueront. |

---


### Installable {#Installable}
Les polices avec ce paramètre indiquent qu'elles peuvent être intégrées et installées de façon permanente sur le système distant par une application. L'utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l'acheteur original, et est soumis au même contrat de licence utilisateur final, droit d'auteur, brevet de design et/ou marque que l'acheteur original.

---

### Restricted {#Restricted}
Les polices qui n'ont que ce bit défini ne doivent pas être modifiées, intégrées ou échangées de quelque manière que ce soit sans obtenir d'abord la permission du propriétaire légal.

---

### PreviewPrint {#PreviewPrint}
Lorsque ce bit est défini, la police peut être intégrée et chargée temporairement sur le système distant. Les documents contenant des polices Preview &amp; Print doivent être ouverts en « lecture seule » ; aucune modification ne peut être appliquée au document.

---

### Editable {#Editable}
Lorsque ce bit est défini, la police peut être intégrée mais ne doit être installée que temporairement sur d'autres systèmes. Contrairement aux polices Preview &amp; Print, les documents contenant des polices Editable peuvent être ouverts en lecture, la modification est autorisée et les changements peuvent être enregistrés.

---

### NoSubsetting {#NoSubsetting}
Lorsque ce bit est défini, la police ne peut pas être sous-ensemble avant l'intégration. D'autres restrictions d'intégration spécifiées dans les bits 0-3 et 9 s'appliquent également.

---

### BitmapOnly {#BitmapOnly}
Lorsque ce bit est défini, seules les bitmaps contenues dans la police peuvent être intégrées. Aucune donnée de contour ne peut être intégrée. S'il n'y a aucune bitmap disponible dans la police, alors la police est considérée comme non intégrable et les services d'intégration échoueront.

---