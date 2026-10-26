---
title: PptOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumun PPT formatında kaydedilmesini kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/pptoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Bir sunumun PPT formatında kaydedilmesini kontrol eden seçenekleri sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Kök dizin girdisinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Kök dizin girdisinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

Kök dizin girdisinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer, 'Microsoft Powerpoint.Slide.8' ile eşleşen '64818D11-4F9B-11CF-86EA-00AA00B929E8' değeridir.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID'yi 'Microsoft Powerpoint.Show.8' olarak ayarla
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```

Kök dizin girdisinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer, 'Microsoft Powerpoint.Slide.8' ile eşleşen '64818D11-4F9B-11CF-86EA-00AA00B929E8' değeridir.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID'yi 'Microsoft Powerpoint.Show.8' olarak ayarla
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |