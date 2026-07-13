---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje uzavřené titulky ve formátu WebVTT.
type: docs
url: /cs/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Reprezentuje uzavřené titulky ve formátu WebVTT.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Vrací globálně jedinečný identifikátor (GUID) uzavřených titulků. |
| [getLabel()](#getLabel--) | Vrací nebo nastavuje štítek uzavřených titulků. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Vrací nebo nastavuje štítek uzavřených titulků. |
| [getBinaryData()](#getBinaryData--) | Vrací binární data uzavřených titulků. |
| [getDataAsString()](#getDataAsString--) | Vrací data uzavřených titulků jako řetězec kódovaný UTF-8. Pouze pro čtení String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Vrací globálně jedinečný identifikátor (GUID) uzavřených titulků. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Vrací nebo nastavuje štítek uzavřených titulků. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Vrací nebo nastavuje štítek uzavřených titulků. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Vrací binární data uzavřených titulků. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Vrací data uzavřených titulků jako řetězec kódovaný UTF-8. Pouze pro čtení String.

**Vrací:**
java.lang.String