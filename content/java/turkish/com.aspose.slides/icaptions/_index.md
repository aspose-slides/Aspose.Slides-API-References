---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: WebVTT kapalı altyazılarını temsil eder.
type: docs
url: /tr/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

WebVTT kapalı altyazılarını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. |
| [getLabel()](#getLabel--) | Kapalı altyazıların etiketini döndürür veya ayarlar. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Kapalı altyazıların etiketini döndürür veya ayarlar. |
| [getBinaryData()](#getBinaryData--) | Kapalı altyazıların ikili verisini döndürür. |
| [getDataAsString()](#getDataAsString--) | Kapalı altyazı verilerini UTF-8 kodlu dize olarak döndürür (Yalnızca okuma) String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. Yalnızca okuma java.util.UUID.

**Döndürür:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Kapalı altyazıların etiketini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Kapalı altyazıların etiketini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Kapalı altyazıların ikili verisini döndürür. Yalnızca okuma byte[].

**Döndürür:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Kapalı altyazı verilerini UTF-8 kodlu dize olarak döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String