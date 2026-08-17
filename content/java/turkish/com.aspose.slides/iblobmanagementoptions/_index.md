---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: Tek bir varlık olarak depolanan ikili veri BLOB (Binary Large Object) bir ses, video ya da sunumun kendisi olabilir.
type: docs
url: /tr/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Büyük ikili nesne (BLOB), tek bir varlık olarak depolanan ikili bir veridir - yani BLOB bir ses, video ya da sunumun kendisi olabilir. BLOB'larla çalışırken bellek tüketimini optimize etmek için bir dizi teknik kullanılır - bu BLOB'lar zaten sunumda depolanmış olabilir ya da daha sonra programatik olarak eklenebilir. [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kullanarak [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrü boyunca BLOB işlemleriyle ilgili farklı davranışları değiştirebilirsiniz.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Bu özellik, Presentation sınıfının bir örneğinin ömrü boyunca kaynak - dosya ya da akışın sahibi olup olamayacağını tanımlar. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Bu özellik, Presentation sınıfının bir örneğinin ömrü boyunca kaynak - dosya ya da akışın sahibi olup olamayacağını tanımlar. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Geçici dosyaların oluşturulacağı kök yol. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Geçici dosyaların oluşturulacağı kök yol. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Bu özellik, Presentation sınıfının bir örneğinin ömrü boyunca kaynak - dosya ya da akışın sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirmeye yardımcı olur, ancak kaynak (akış ya da dosya) Presentation örneğinin ömrü boyunca değiştirilemez. Bir örnek:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Presentation ömrü boyunca pres.pptx kilitlendiği için IOException atılacak
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation nesnesi yok edildiğinde, dosya kilidi açılır ve silinebilir
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Döndürür:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Bu özellik, Presentation sınıfının bir örneğinin ömrü boyunca kaynak - dosya ya da akışın sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirmeye yardımcı olur, ancak kaynak (akış ya da dosya) Presentation örneğinin ömrü boyunca değiştirilemez. Bir örnek:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Presentation ömrü boyunca pres.pptx kilitlendiği için IOException atılacak
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation nesnesi yok edildiğinde, dosya kilidi açılır ve silinebilir
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir.

--------------------

Sunumla çalışma tamamlandıktan sonra tüm dosyalar silinecektir.

**Döndürür:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir.

--------------------

Sunumla çalışma tamamlandıktan sonra tüm dosyalar silinecektir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistemin geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Döndürür:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistemin geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellek içinde tutmak performansı maksimize eder ancak yüksek bellek kullanımıyla sonuçlanabilir. Bu özelliği ortamınıza ya da gereksinimlerinize göre ayarlayın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında göz ardı edilir, çünkü o zaman bellek tek depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın etkisi olmaz.

--------------------

Varsayılan değer 629 145 600 bayt (600 MB)’dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır.

**Döndürür:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellek içinde tutmak performansı maksimize eder ancak yüksek bellek kullanımıyla sonuçlanabilir. Bu özelliği ortamınıza ya da gereksinimlerinize göre ayarlayın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında göz ardı edilir, çünkü o zaman bellek tek depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın etkisi olmaz.

--------------------

Varsayılan değer 629 145 600 bayt (600 MB)’dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |