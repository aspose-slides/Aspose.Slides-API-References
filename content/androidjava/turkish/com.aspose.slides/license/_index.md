---
title: License
second_title: Aspose.Slides for Android via Java API Referansı
description: Bileşeni lisanslamak için yöntemler sağlar.
type: docs
url: /tr/com.aspose.slides/license/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Bileşeni lisanslamak için yöntemler sağlar.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) | Bu sınıfın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
| [getVersion()](#getVersion--) | Java aracılığıyla Android için Aspose.Slides sürümünü döndürür. |
| [resetLicense()](#resetLicense--) | Lisansı sıfırla. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Bu sınıfın yeni bir örneğini başlatır.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

Bileşeni lisanslar.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Lisansı içeren bir akış. Değerlendirme moduna geçmek için null kullanın. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Bileşeni lisanslar.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namePath | java.lang.String | Tam veya kısa bir dosya adı ya da gömülü bir kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Java aracılığıyla Android için Aspose.Slides sürümünü döndürür.

**Döndürür:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Lisansı sıfırlar. Bu yöntemi bileşende lisansı sıfırlamak için kullanın.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Bileşene lisans uygulanıp uygulanmadığını kontrol eder.

**Döndürür:**
boolean