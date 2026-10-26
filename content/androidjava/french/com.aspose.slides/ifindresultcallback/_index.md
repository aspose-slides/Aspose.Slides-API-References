---
title: IFindResultCallback
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Interface de rappel utilisée pour obtenir le résultat de recherche de texte.
type: docs
url: /fr/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Interface de rappel utilisée pour obtenir le résultat de recherche de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Méthode de rappel qui reçoit les données concernant le texte trouvé. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Méthode de rappel qui reçoit les données concernant le texte trouvé.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Le [ITextFrame](../../com.aspose.slides/itextframe) dans lequel le texte a été trouvé. |
| sourceText | java.lang.String | Le texte source dans lequel le texte a été trouvé. |
| foundText | java.lang.String | Le texte trouvé. |
| textPosition | int | La position du texte trouvé. |