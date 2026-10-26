---
title: IAIWebClient
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Rozhraní AI Web klienta.
type: docs
url: /cs/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web client interface. Toto rozhraní umožňuje nahradit různé AI jazykové modely. Třídy, které toto rozhraní implementují, by měly být používány spolu se SlidesAIAgent.
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odešle chat instrukci do AI modelu pomocí poskytnuté instance HttpConnection a vrátí odpovědní zprávu k dané instrukci. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Odešle chat instrukci do AI modelu pomocí poskytnuté instance HttpConnection a vrátí odpovědní zprávu k dané instrukci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována AI modelem. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná AI modelem jako odpověď na danou instrukci.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání konverzace zachovávají celý kontext.

**Návratová hodnota:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) instance.