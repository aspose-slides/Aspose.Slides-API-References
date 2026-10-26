---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Bileşeni lisanslamak için yöntemler sağlar.
type: docs
url: /tr/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Bileşeni lisanslamak için yöntemler sağlar.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
### Yöntemler

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
| [resetLicense()](#resetLicense--) | Lisansı sıfırlar |
| [isLicensed()](#isLicensed--) | Lisansın bileşene uygulanıp uygulanmadığını kontrol eder |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Bileşeni lisanslar.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Tam veya kısa dosya adı ya da gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Bileşen derlemesinin klasörü.

3. İstemcinin çağıran derlemesinin klasörü.

4. Giriş derlemesinin klasörü.

5. İstemcinin çağıran derlemesindeki gömülü kaynak. |
### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Bileşeni lisanslar.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Lisansı içeren bir akış. |

Bu yöntemi bir akıştan lisans yüklemek için kullanın. |
### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Lisansı sıfırla

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Bu yöntemi bileşende lisansı sıfırlamak için kullanın

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Lisansın bileşene uygulanıp uygulanmadığını kontrol eder

**Döndürür:**
boolean - bileşen lisanslıysa true, aksi takdirde false