---
title: BlobManagementOptions
second_title: Aspose.Slides for Java API Referansı
description: BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.

## Constructors

| Constructor | Description |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Yeni varsayılan blob yönetim seçenekleri oluşturur. |

## Methods

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak — dosya ya da akış — sahibi olup olamayacağını tanımlar. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak — dosya ya da akış — sahibi olup olamayacağını tanımlar. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Geçici dosyaların oluşturulacağı kök yol. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Geçici dosyaların oluşturulacağı kök yol. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Yeni varsayılan blob yönetim seçenekleri oluşturur.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak — dosya ya da akış — sahibi olup olamayacağını tanımlar. Örnek sahibi ise kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak Presentation örneği süresince kaynak (akış ya da dosya) değiştirilemez.

**Returns:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak — dosya ya da akış — sahibi olup olamayacağını tanımlar. Örnek sahibi ise kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak Presentation örneği süresince kaynak (akış ya da dosya) değiştirilemez.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Returns:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistemin geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Returns:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistemin geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ların bellek içinde tutulması performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında yok sayılır, çünkü o zaman belleğin tek depolama konumu olması nedeniyle bellek içi BLOB kullanımını sınırlamanın bir etkisi olmaz.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)'dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek ayrılacaktır.

**Returns:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Tüm BLOB'ların bellek içinde kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ların bellek içinde tutulması performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında yok sayılır, çünkü o zaman belleğin tek depolama konumu olması nedeniyle bellek içi BLOB kullanımını sınırlamanın bir etkisi olmaz.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)'dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek ayrılacaktır.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |