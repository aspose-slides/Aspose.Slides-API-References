---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un'istanza di conversazione.
type: docs
url: /it/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Rappresenta un'istanza di conversazione. Diversamente dalle chiamate AI regolari, le conversazioni conservano l'intero contesto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Invia un messaggio di richiesta di conversazione includendo l'intero contesto e restituisce la risposta. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Invia un messaggio di richiesta di conversazione includendo l'intero contesto e restituisce la risposta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String | L'istruzione o il messaggio da elaborare dal modello AI. |

**Restituisce:**
java.lang.String - Il messaggio generato dal modello AI in risposta all'istruzione fornita nel contesto della conversazione.