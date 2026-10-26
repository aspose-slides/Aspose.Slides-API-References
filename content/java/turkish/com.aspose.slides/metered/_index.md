---
title: Metered
second_title: Aspose.Slides for Java API Referansı
description: Sayaçlı anahtarı ayarlamak için yöntemler sağlar.
type: docs
url: /tr/com.aspose.slides/metered/
---
**Kalıtım:**
java.lang.Object
```
public class Metered
```

Sayaçlı anahtarı ayarlamak için yöntemler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) | Bu sınıfın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sayaçlı genel ve özel anahtarı ayarlar. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Tüketim dosyası boyutunu alır |
| [getConsumptionCredit()](#getConsumptionCredit--) | Tüketim kredisini alır |
| [isMeteredLicensed()](#isMeteredLicensed--) | Sayaçlı lisansın olup olmadığını kontrol eder |
### Metered() {#Metered--}
```
public Metered()
```

Bu sınıfın yeni bir örneğini başlatır.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Sayaçlı genel ve özel anahtarı ayarlar. Eğer sayaçlı lisans satın alırsanız, uygulamayı başlatırken bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak tüketim verileri yüklenemediğinde ve 24 saat aşılırsa lisans değerlendirme durumuna geçer, böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol edip, değerlendirme durumunda ise bu API'yi tekrar çağırmalısınız.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | genel anahtar |
| privateKey | java.lang.String | özel anahtar |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Tüketim dosyası boyutunu alır

**Döndürür:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Tüketim kredisini alır

**Döndürür:**
double - tüketim miktarı

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Sayaçlı lisansın olup olmadığını kontrol eder

**Döndürür:**
boolean - Doğru veya Yanlış