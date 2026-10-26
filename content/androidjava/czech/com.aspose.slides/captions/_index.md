---
title: Captions
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje uzavřené titulky WebVTT.
type: docs
url: /cs/com.aspose.slides/captions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Reprezentuje uzavřené titulky WebVTT.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Vrací globálně jedinečný identifikátor (GUID) uzavřených titulků. |
| [getLabel()](#getLabel--) | Vrací nebo nastavuje štítek uzavřených titulků. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Vrací nebo nastavuje štítek uzavřených titulků. |
| [getBinaryData()](#getBinaryData--) | Vrací binární data uzavřených titulků. |
| [getDataAsString()](#getDataAsString--) | Vrací data uzavřených titulků jako řetězec kódovaný UTF-8 Pouze pro čtení String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Vrací globálně jedinečný identifikátor (GUID) uzavřených titulků. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Vrací nebo nastavuje štítek uzavřených titulků. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Vrací nebo nastavuje štítek uzavřených titulků. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Vrací binární data uzavřených titulků. Pouze pro čtení byte[] .

**Vrací:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Vrací data uzavřených titulků jako řetězec kódovaný UTF-8 Pouze pro čtení String.

**Vrací:**
java.lang.String