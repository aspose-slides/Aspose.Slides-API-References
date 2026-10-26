---
title: IPptOptions
second_title: Aspose.Slides Android için Java API Referansı
description: Bir sunumun PPT formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/ipptoptions/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Bir sunumun PPT formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM etkinleştirmesi için kullanılabilir. Varsayılan değer, '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.

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
public abstract void setRootDirectoryClsid(UUID value)
```

Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM etkinleştirmesi için kullanılabilir. Varsayılan değer, '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.

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