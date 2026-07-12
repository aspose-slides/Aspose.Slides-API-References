---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Bileşeni lisanslamak için metodlar sağlar.
type: docs
url: /tr/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Bileşeni lisanslamak için metodlar sağlar.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Metodlar

| Metot | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | java.lang.String | Tam veya kısa bir dosya adı veya gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

--------------------

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.
2. Bileşen derlemesinin klasörü.
3. İstemcinin çağıran derlemesinin klasörü.
4. Giriş derlemesinin klasörü.
5. İstemcinin çağıran derlemesinde gömülü bir kaynak. |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Lisansı içeren bir akış. |

--------------------

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

Lisansın bileşene uygulanıp uygulanmadığını kontrol edin

**Döndürür:**
boolean - bileşen lisanslıysa true, aksi halde false