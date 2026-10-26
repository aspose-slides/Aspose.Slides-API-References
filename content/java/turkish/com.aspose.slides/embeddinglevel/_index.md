---
title: EmbeddingLevel
second_title: Aspose.Slides for Java API Referansı
description: Yazı tipinin gömülmesi için lisans haklarını temsil eder.
type: docs
url: /tr/com.aspose.slides/embeddinglevel/
---
**Miras:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Yazı tipinin gömülmesi için lisans haklarını temsil eder.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Installable](#Installable) | Bu ayara sahip yazı tipleri, bir uygulama tarafından uzak sistemde gömülebileceğini ve kalıcı olarak kurulabileceğini gösterir. |
| [Restricted](#Restricted) | Yalnızca bu bit ayarlanmış yazı tipleri, yasal sahibinden izin alınmadan hiçbir şekilde değiştirilemez, gömülemez veya takas edilemez. |
| [PreviewPrint](#PreviewPrint) | Bu bit ayarlandığında, yazı tipi gömülebilir ve uzak sistemde geçici olarak yüklenebilir. |
| [Editable](#Editable) | Bu bit ayarlandığında, yazı tipi gömülebilir ancak diğer sistemlerde yalnızca geçici olarak kurulmalıdır. |
| [NoSubsetting](#NoSubsetting) | Bu bit ayarlandığında, yazı tipi gömülmeden önce altkümelendirilmemelidir. |
| [BitmapOnly](#BitmapOnly) | Bu bit ayarlandığında, yalnızca yazı tipinde bulunan bitmapler gömülebilir. |

### Kurulabilir {#Installable}
```
public static final int Installable
```

Bu ayara sahip yazı tipleri, bir uygulama tarafından uzak sistemde gömülebileceğini ve kalıcı olarak kurulabileceğini gösterir. Uzak sistemin kullanıcısı, bu yazı tipi için orijinal alıcıyla aynı hakları, yükümlülükleri ve lisansları elde eder ve orijinal alıcı gibi aynı son kullanıcı lisans sözleşmesi, telif hakkı, tasarım patenti ve/veya ticari marka koşullarına tabidir.

### Kısıtlı {#Restricted}
```
public static final int Restricted
```

Yalnızca bu bit ayarlanmış yazı tipleri, yasal sahibinden izin alınmadan hiçbir şekilde değiştirilemez, gömülemez veya takas edilemez.

### ÖnizlemeYazdır {#PreviewPrint}
```
public static final int PreviewPrint
```

Bu bit ayarlandığında, yazı tipi gömülebilir ve uzak sistemde geçici olarak yüklenebilir. Önizleme ve Yazdırma yazı tiplerini içeren belgeler yalnızca “salt okunur” olarak açılmalıdır; belgeye hiçbir düzenleme uygulanamaz.

### Düzenlenebilir {#Editable}
```
public static final int Editable
```

Bu bit ayarlandığında, yazı tipi gömülebilir ancak diğer sistemlerde yalnızca geçici olarak kurulmalıdır. Önizleme ve Yazdırma yazı tiplerinin aksine, Düzenlenebilir yazı tiplerini içeren belgeler okuma için açılabilir, düzenleme yapılabilir ve değişiklikler kaydedilebilir.

### AltkümelemeYok {#NoSubsetting}
```
public static final int NoSubsetting
```

Bu bit ayarlandığında, yazı tipi gömülmeden önce altkümelendirilmemelidir. Bit 0-3 ve 9’da belirtilen diğer gömme kısıtlamaları da geçerlidir.

### YalnızcaBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Bu bit ayarlandığında, yalnızca yazı tipinde bulunan bitmapler gömülebilir. Çizgi (outline) verileri gömülemez. Yazı tipinde bitmap bulunmuyorsa, yazı tipi gömülemez kabul edilir ve gömme hizmetleri başarısız olur.