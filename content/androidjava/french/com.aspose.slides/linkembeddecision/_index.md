---
title: LinkEmbedDecision
second_title: Aspose.Slides pour Android via la référence API Java
description: Détermine comment l'objet sera traité lors de l'enregistrement.
type: docs
url: /fr/com.aspose.slides/linkembeddecision/
---
**Héritage:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Détermine comment l'Object sera traité lors de l'enregistrement.
## Champs

| Champ | Description |
| --- | --- |
| [Link](#Link) | L'Object sera stocké à l'extérieur, référencé par URL |
| [Embed](#Embed) | L'Object doit être intégré à un fichier généré si possible. |
| [Ignore](#Ignore) | L'Object sera ignoré. |
### Lien {#Link}
```
public static final int Link
```


L'Object sera stocké à l'extérieur, référencé par URL

### Intégrer {#Embed}
```
public static final int Embed
```


L'Object doit être intégré à un fichier généré si possible. Si l'intégration est impossible, GetUrl sera appelé et, selon le résultat, l'Object sera référencé par URL ou ignoré.

### Ignorer {#Ignore}
```
public static final int Ignore
```


L'Object sera ignoré.