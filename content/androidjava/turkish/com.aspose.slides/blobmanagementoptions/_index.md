---
title: BlobManagementOptions
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/blobmanagementoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Yeni varsayılan blob yönetim seçenekleri oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Geçici dosyaların oluşturulacağı kök yol. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Geçici dosyaların oluşturulacağı kök yol. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Bellekte yer kaplayabilecek tüm BLOB'ların maksimum toplam boyutunu (bayt cinsinden) tanımlar. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Bellekte yer kaplayabilecek tüm BLOB'ların maksimum toplam boyutunu (bayt cinsinden) tanımlar. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Yeni varsayılan blob yönetim seçenekleri oluşturur.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. Örnek sahibi ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak kaynak (akış veya dosya) Presentation örneğinin yaşam süresi boyunca değiştirilemez.

**Döndürür:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. Örnek sahibi ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı iyileştirir, ancak kaynak (akış veya dosya) Presentation örneğinin yaşam süresi boyunca değiştirilemez.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Döndürür:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerektirir.

--------------------

Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistem geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Döndürür:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak sistem geçici dizini kullanılacaktır. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır yalnızca aşıldığında alternatif mekanizmalar (örneğin geçici dosyalar) devreye girer. BLOB'ların bellekte tutulması performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına neden olabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında göz ardı edilir; çünkü o zaman hafıza tek depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın bir etkisi yoktur.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)’dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır.

**Döndürür:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır yalnızca aşıldığında alternatif mekanizmalar (örneğin geçici dosyalar) devreye girer. BLOB'ların bellekte tutulması performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına neden olabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı ayarlamak için kullanın.

--------------------

Bu özellik, \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) false olarak ayarlandığında göz ardı edilir; çünkü o zaman hafıza tek depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın bir etkisi yoktur.

--------------------

Varsayılan değer 629.145.600 bayt (600 MB)’dır.

--------------------

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |