---
title: LinkEmbedDecision
second_title: Référence de l'API Aspose.Slides pour Java
description: Détermine comment l'objet sera traité lors de l'enregistrement.
type: docs
url: /fr/com.aspose.slides/linkembeddecision/
---
**Héritage:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Détermine comment l'objet sera traité lors de l'enregistrement.
## Champs

| Champ | Description |
| --- | --- |
| [Link](#Link) | L'objet sera stocké à l'extérieur, référencé par URL |
| [Embed](#Embed) | L'objet doit être incorporé dans un fichier généré si possible. |
| [Ignore](#Ignore) | L'objet sera ignoré. |
### Lien {#Link}
```
public static final int Link
```

L'objet sera stocké à l'extérieur, référencé par URL

### Incorporer {#Embed}
```
public static final int Embed
```

L'objet doit être incorporé dans un fichier généré si possible. Si l'intégration est impossible, GetUrl sera appelé et, selon le résultat, l'objet sera référencé par URL ou ignoré.

### Ignorer {#Ignore}
```
public static final int Ignore
```

L'objet sera ignoré.