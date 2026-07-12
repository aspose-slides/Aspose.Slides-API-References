---
title: EmbeddingLevel
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Fontun gömülmesi için lisans haklarını temsil eder.
type: docs
url: /tr/com.aspose.slides/embeddinglevel/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Fontun gömülmesi için lisans haklarını temsil eder.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Installable](#Installable) | Bu ayara sahip fontlar, bir uygulama tarafından uzak sisteme gömülebilir ve kalıcı olarak kurulabilir olduğunu gösterir. |
| [Restricted](#Restricted) | Yalnızca bu bit ayarlı olan fontlar, yasal sahibinin izni alınmadan hiçbir şekilde değiştirilmemeli, gömülmemeli veya değiş tokuş edilmemelidir. |
| [PreviewPrint](#PreviewPrint) | Bu bit ayarlandığında, font gömülebilir ve uzak sistemde geçici olarak yüklenebilir. |
| [Editable](#Editable) | Bu bit ayarlandığında, font gömülebilir ancak diğer sistemlerde yalnızca geçici olarak kurulmalıdır. |
| [NoSubsetting](#NoSubsetting) | Bu bit ayarlandığında, font gömülmeden önce alt küme oluşturulamaz. |
| [BitmapOnly](#BitmapOnly) | Bu bit ayarlandığında, yalnızca font içinde bulunan bitmapler gömülebilir. |
### Yüklenebilir {#Installable}
```
public static final int Installable
```

Bu ayara sahip fontlar, bir uygulama tarafından uzak sisteme gömülebilir ve kalıcı olarak kurulabilir olduğunu gösterir. Uzak sistemin kullanıcısı, o font için orijinal alıcı ile aynı hak, yükümlülük ve lisansları edinir ve orijinal alıcı gibi aynı son-kullanıcı lisans sözleşmesi, telif hakkı, tasarım patenti ve/veya ticari marka koşullarına tabidir.

### Kısıtlı {#Restricted}
```
public static final int Restricted
```

Yalnızca bu bit ayarlı olan fontlar, yasal sahibinin izni alınmadan hiçbir şekilde değiştirilmemeli, gömülmemeli veya değiş tokuş edilmemelidir.

### ÖnizlemeVeYazdırma {#PreviewPrint}
```
public static final int PreviewPrint
```

Bu bit ayarlandığında, font gömülebilir ve uzak sistemde geçici olarak yüklenebilir. Önizleme ve Yazdırma fontlarını içeren belgeler "yalnızca-okunur" olarak açılmalıdır; belgeye hiçbir düzenleme uygulanamaz.

### Düzenlenebilir {#Editable}
```
public static final int Editable
```

Bu bit ayarlandığında, font gömülebilir ancak diğer sistemlerde yalnızca geçici olarak kurulmalıdır. Önizleme ve Yazdırma fontlarının aksine, Düzenlenebilir fontları içeren belgeler okuma amacıyla açılabilir, düzenleme yapılabilir ve değişiklikler kaydedilebilir.

### AltKümeOlusturmaYok {#NoSubsetting}
```
public static final int NoSubsetting
```

Bu bit ayarlandığında, font gömülmeden önce alt küme oluşturulamaz. Bit 0-3 ve 9'da belirtilen diğer gömme kısıtlamaları da geçerlidir.

### YalnızcaBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Bu bit ayarlandığında, yalnızca font içinde bulunan bitmapler gömülebilir. Kontur verileri gömülemez. Fontta bitmap bulunmuyorsa, font gömülemez kabul edilir ve gömme hizmetleri başarısız olur.