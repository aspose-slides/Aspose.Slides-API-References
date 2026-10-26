---
title: Metered
second_title: Aspose.Slides for Android için Java API Referansı
description: Metered anahtarını ayarlamak için yöntemler sağlar.
type: docs
url: /tr/com.aspose.slides/metered/
---
**Kalıtım:**
java.lang.Object
```
public class Metered
```

Metered anahtarı ayarlamak için yöntemler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) | Bu sınıfın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered genel ve özel anahtarı ayarlar. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Tüketim dosyası boyutunu alır |
| [getConsumptionCredit()](#getConsumptionCredit--) | Tüketim kredisini alır |
| [isMeteredLicensed()](#isMeteredLicensed--) | Metered lisanslı mı kontrol eder |
### Metered() {#Metered--}
```
public Metered()
```

Bu sınıfın yeni bir örneğini başlatır.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Metered genel ve özel anahtarı ayarlar. Eğer metered lisans satın alırsanız, uygulamayı başlatırken bu API çağrılmalıdır; genellikle bu yeterlidir. Ancak tüketim verileri her zaman yüklenemez ve 24 saat aşarsa, lisans değerlendirme durumuna geçer; böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumu ise bu API’yi tekrar çağırın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | public anahtar |
| privateKey | java.lang.String | private anahtar |

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

Metered lisanslı mı kontrol eder

**Döndürür:**
boolean - True veya false