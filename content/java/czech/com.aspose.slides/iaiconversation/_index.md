---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Represents a conversation instance.
type: docs
url: /cs/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Představuje instanci konverzace. Na rozdíl od běžných AI volání konverzace zachovávají celý kontext.
## Metody

| Metoda | Popis |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Odesílá požadavek konverzace včetně celého kontextu a vrací odpověď. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Odesílá požadavek konverzace včetně celého kontextu a vrací odpověď.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována AI modelem. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná AI modelem jako odpověď na zadanou instrukci v kontextu konverzace.