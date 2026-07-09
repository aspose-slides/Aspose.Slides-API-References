---
title: EmbeddingLevel
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente les droits de licence pour l'incorporation de la police.
type: docs
url: /fr/com.aspose.slides/embeddinglevel/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Représente les droits de licence pour l’incorporation de la police.
## Champs

| Champ | Description |
| --- | --- |
| [Installable](#Installable) | Les polices avec ce paramètre indiquent qu’elles peuvent être incorporées et installées de façon permanente sur le système distant par une application. |
| [Restricted](#Restricted) | Les polices qui n’ont que ce bit activé ne doivent pas être modifiées, incorporées ou échangées de quelque manière que ce soit sans d’abord obtenir l’autorisation du propriétaire légal. |
| [PreviewPrint](#PreviewPrint) | Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. |
| [Editable](#Editable) | Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée que temporairement sur d’autres systèmes. |
| [NoSubsetting](#NoSubsetting) | Lorsque ce bit est activé, la police ne peut pas être sous-ensemble avant incorporation. |
| [BitmapOnly](#BitmapOnly) | Lorsque ce bit est activé, seuls les bitmap contenus dans la police peuvent être incorporés. |
### Installable {#Installable}
```
public static final int Installable
```

Les polices avec ce paramètre indiquent qu’elles peuvent être incorporées et installées de façon permanente sur le système distant par une application. L’utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l’acheteur original, et est soumis au même accord de licence utilisateur final, droit d’auteur, brevet de design et/ou marque déposée que celui de l’acheteur original.

### Restricted {#Restricted}
```
public static final int Restricted
```

Les polices qui n’ont que ce bit activé ne doivent pas être modifiées, incorporées ou échangées de quelque manière que ce soit sans d’abord obtenir l’autorisation du propriétaire légal.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. Les documents contenant des polices Preview & Print doivent être ouverts « lecture-seule » ; aucune modification ne peut être appliquée au document.

### Editable {#Editable}
```
public static final int Editable
```

Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée que temporairement sur d’autres systèmes. Contrairement aux polices Preview & Print, les documents contenant des polices Editable peuvent être ouverts en lecture, la modification est autorisée et les changements peuvent être enregistrés.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Lorsque ce bit est activé, la police ne peut pas être sous-ensemble avant incorporation. D’autres restrictions d’incorporation spécifiées dans les bits 0-3 et 9 s’appliquent également.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Lorsque ce bit est activé, seuls les bitmap contenus dans la police peuvent être incorporés. Aucune donnée de contour ne peut être incorporée. S’il n’existe aucun bitmap disponible dans la police, alors la police est considérée comme non incorporable et les services d’incorporation échoueront.