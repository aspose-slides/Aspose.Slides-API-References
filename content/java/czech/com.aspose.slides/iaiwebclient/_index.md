---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI Web client interface.
type: docs
url: /cs/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Rozhraní AI Web klienta. Toto rozhraní umožňuje nahrazovat různé modely AI jazyků. Třídy, které implementují toto rozhraní, by měly být používány spolu s SlidesAIAgent.
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odesílá chatovou instrukci modelu AI pomocí poskytnutého instance HttpConnection a vrací odpovědní zprávu na danou instrukci. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Odesílá chatovou instrukci modelu AI pomocí poskytnutého instance HttpConnection a vrací odpovědní zprávu na danou instrukci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována modelem AI. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná modelem AI jako odpověď na danou instrukci.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání si konverzace uchovávají celý kontext.

**Návratová hodnota:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instanci [IAIConversation](../../com.aspose.slides/iaiconversation).