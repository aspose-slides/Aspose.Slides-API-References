---
title: Captions
second_title: Aspose.Slides for Android via Java API Referansı
description: WebVTT kapalı altyazılarını temsil eder.
type: docs
url: /tr/com.aspose.slides/captions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

WebVTT kapalı altyazılarını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. |
| [getLabel()](#getLabel--) | Kapalı altyazıların etiketini döndürür veya ayarlar. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Kapalı altyazıların etiketini döndürür veya ayarlar. |
| [getBinaryData()](#getBinaryData--) | Kapalı altyazıların ikili verisini döndürür. |
| [getDataAsString()](#getDataAsString--) | Kapalı altyazı verilerini UTF-8 kodlu dize olarak döndürür Yalnızca okunur String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. Yalnızca okunur java.util.UUID.

**Döndürür:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

Kapalı altyazıların etiketini döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

Kapalı altyazıların etiketini döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Kapalı altyazıların ikili verisini döndürür. Yalnızca okunur  byte[] .

**Döndürür:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

Kapalı altyazı verilerini UTF-8 kodlu dize olarak döndürür Yalnızca okunur String.

**Döndürür:**
java.lang.String