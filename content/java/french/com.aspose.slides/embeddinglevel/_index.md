---
title: EmbeddingLevel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les droits de licence pour l'incorporation de la police.
type: docs
url: /fr/com.aspose.slides/embeddinglevel/
---
**Héritage:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Représente les droits de licence pour l'incorporation de la police.
## Champs

| Champ | Description |
| --- | --- |
| [Installable](#Installable) | Les polices avec ce paramètre indiquent qu'elles peuvent être incorporées et installées de façon permanente sur le système distant par une application. |
| [Restricted](#Restricted) | Les polices qui ont uniquement ce bit activé ne doivent pas être modifiées, incorporées ou échangées de quelque manière que ce soit sans d'abord obtenir l'autorisation du propriétaire légal. |
| [PreviewPrint](#PreviewPrint) | Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. |
| [Editable](#Editable) | Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée temporairement que sur d'autres systèmes. |
| [NoSubsetting](#NoSubsetting) | Lorsque ce bit est activé, la police ne doit pas être sous-ensemble avant d'être incorporée. |
| [BitmapOnly](#BitmapOnly) | Lorsque ce bit est activé, seuls les bitmaps contenus dans la police peuvent être incorporés. |
### Installable {#Installable}
```
public static final int Installable
```

Les polices avec ce paramètre indiquent qu’elles peuvent être incorporées et installées de façon permanente sur le système distant par une application. L'utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l'acheteur initial, et est soumis au même accord de licence utilisateur final, aux droits d’auteur, au brevet de design et/ou à la marque déposée que l'acheteur initial.

### Restreint {#Restricted}
```
public static final int Restricted
```

Les polices qui ont uniquement ce bit activé ne doivent pas être modifiées, incorporées ou échangées de quelque manière que ce soit sans d'abord obtenir l'autorisation du propriétaire légal.

### AperçuImpression {#PreviewPrint}
```
public static final int PreviewPrint
```

Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. Les documents contenant des polices Aperçu & Impression doivent être ouverts en lecture seule ; aucune modification ne peut être appliquée au document.

### Modifiable {#Editable}
```
public static final int Editable
```

Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée temporairement que sur d'autres systèmes. Contrairement aux polices Aperçu & Impression, les documents contenant des polices Modifiables peuvent être ouverts en lecture, la modification est autorisée et les modifications peuvent être enregistrées.

### PasDeSousEnsembles {#NoSubsetting}
```
public static final int NoSubsetting
```

Lorsque ce bit est activé, la police ne doit pas être sous-ensemble avant d'être incorporée. D'autres restrictions d'incorporation spécifiées dans les bits 0-3 et 9 s'appliquent également.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Lorsque ce bit est activé, seuls les bitmap contenus dans la police peuvent être incorporés. Aucune donnée de contour ne peut être incorporée. S'il n'y a aucun bitmap disponible dans la police, celle-ci est considérée comme non incorporable et les services d'incorporation échoueront.