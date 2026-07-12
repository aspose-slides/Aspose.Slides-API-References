---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /tr/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Bir Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili bir veridir - yani BLOB bir ses, video veya sunumun kendisi olabilir. BLOB'larla çalışan sırada bellek tüketimini optimize etmek için çeşitli teknikler kullanılır - bu, zaten sunumda depolanmış olabilir veya daha sonra programatik olarak eklenebilir. [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kullanarak [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrü boyunca BLOB'ların işlenmesiyle ilgili farklı davranış yönlerini değiştirebilirsiniz.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Bu özellik, Presentation sınıfının bir örneğinin ömür boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Bu özellik, Presentation sınıfının bir örneğinin ömür boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Geçici dosyaların oluşturulacağı kök yol. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Geçici dosyaların oluşturulacağı kök yol. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Bu özellik, Presentation sınıfının bir örneğinin ömür boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak kaynak (akış veya dosya) Presentation örneğinin ömrü boyunca değiştirilemez. Bu bir örnektir:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException, pres.pptx bir Presentation ömrü boyunca kilitli olduğu için fırlatılacaktır
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation nesnesi serbest bırakıldıktan sonra, dosya kilidi açılır ve silinebilir
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
```

**Döndürür:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Bu özellik, Presentation sınıfının bir örneğinin ömür boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak kaynak (akış veya dosya) Presentation örneğinin ömrü boyunca değiştirilemez. Bu bir örnektir:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException, pres.pptx bir Presentation ömrü boyunca kilitli olduğu için fırlatılacaktır
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation nesnesi serbest bırakıldıktan sonra, dosya kilidi açılır ve silinebilir
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Döndürür:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistem geçici dizini kullanılır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Döndürür:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistem geçici dizini kullanılır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınıra ulaşıldığında yalnızca alternatif mekanizmalar (örneğin geçici dosyalar) devreye girer. BLOB'ları bellekte tutmak performansı maksimize eder ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellekteki BLOB kullanımını sınırlamanın bir etkisi olmaz.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)'dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek ayrılacaktır.

**Döndürür:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınıra ulaşıldığında yalnızca alternatif mekanizmalar (örneğin geçici dosyalar) devreye girer. BLOB'ları bellekte tutmak performansı maksimize eder ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellekteki BLOB kullanımını sınırlamanın bir etkisi olmaz.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)'dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek ayrılacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |