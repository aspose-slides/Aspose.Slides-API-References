---
title: IAIConversation
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Zastupuje instanci konverzace.
type: docs
url: /cs/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Zastupuje instanci konverzace. Na rozdíl od běžných volání AI konverzace zachovávají celý kontext.
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
| instruction | java.lang.String | Instrukce nebo zpráva, kterou má AI model zpracovat. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná AI modelem jako odpověď na danou instrukci v kontextu konverzace.