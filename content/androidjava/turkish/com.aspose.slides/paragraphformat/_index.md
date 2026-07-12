---
title: ParagraphFormat
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/paragraphformat/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Gerçekleştirilen Arabirimler:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "undefined" anlamına gelen değerler alırsınız.

Kalıtım dahil etkili biçimlendirme parametresi değerlerini almak için [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) yöntemini kullanmanız gerekir; bu yöntem bir [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) örneği döndürür.

## Yapıcılar

| Constructor | Description |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | [ParagraphFormat](../../com.aspose.slides/paragraphformat) sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBullet()](#getBullet--) | Paragrafın madde işareti biçimini döndürür. |
| [getDepth()](#getDepth--) | Paragrafın derinliğini döndürür veya ayarlar. |
| [setDepth(short value)](#setDepth-short-) | Paragrafın derinliğini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Kalıtım olmadan bir paragraftaki metin hizalamasını döndürür veya ayarlar. |
| [setAlignment(int value)](#setAlignment-int-) | Kalıtım olmadan bir paragraftaki metin hizalamasını döndürür veya ayarlar. |
| [getSpaceWithin()](#getSpaceWithin--) | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. |
| [getSpaceBefore()](#getSpaceBefore--) | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. |
| [getSpaceAfter()](#getSpaceAfter--) | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür veya ayarlar. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür veya ayarlar. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. |
| [getRightToLeft()](#getRightToLeft--) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. |
| [getMarginLeft()](#getMarginLeft--) | Kalıtım olmadan bir paragrafta sol kenar boşluğunu döndürür veya ayarlar. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Kalıtım olmadan bir paragrafta sol kenar boşluğunu döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Kalıtım olmadan bir paragrafta sağ kenar boşluğunu döndürür veya ayarlar. |
| [setMarginRight(float value)](#setMarginRight-float-) | Kalıtım olmadan bir paragrafta sağ kenar boşluğunu döndürür veya ayarlar. |
| [getIndent()](#getIndent--) | Kalıtım olmadan paragrafın İlk Satır Girintisini/Sarkan Girintisini döndürür veya ayarlar. |
| [setIndent(float value)](#setIndent-float-) | Kalıtım olmadan paragrafın İlk Satır Girintisini/Sarkan Girintisini döndürür veya ayarlar. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. |
| [getTabs()](#getTabs--) | Paragrafın sekmelerini döndürür. |
| [getFontAlignment()](#getFontAlignment--) | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Paragrafın varsayılan bölüm biçimini döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

[ParagraphFormat](../../com.aspose.slides/paragraphformat) sınıfının yeni bir örneğini başlatır.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Paragrafın madde işareti biçimini döndürür. Yalnızca okunabilir [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Döndürür:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0 tanımsız değeri ifade eder. Okunup-yazılabilir short .

**Döndürür:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0 tanımsız değeri ifade eder. Okunup-yazılabilir short .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Kalıtım olmadan bir paragrafta metin hizalamasını döndürür veya ayarlar. Okunup-yazılabilir [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Bir PPTX dosyasını temsil eden Presentation nesnesini oluşturun
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // İlk slaytı alıyor
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Slayttaki birinci ve ikinci yer tutucuya erişiliyor ve AutoShape olarak tip dönüşümü yapılıyor
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Her iki yer tutucudaki metni değiştir
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Yer tutucuların ilk paragrafını alıyor
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Metin paragrafını ortaya hizalıyor
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Sunumu PPTX dosyası olarak kaydediyor
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Kalıtım olmadan bir paragrafta metin hizalamasını döndürür veya ayarlar. Okunup-yazılabilir [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Bir PPTX dosyasını temsil eden Presentation nesnesini oluşturun
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // İlk slaytı alıyor
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Slayttaki birinci ve ikinci yer tutucuya erişiliyor ve AutoShape olarak tip dönüşümü yapılıyor
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Her iki yer tutucudaki metni değiştir
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Yer tutucuların ilk paragrafını alıyor
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Metin paragrafını ortaya hizalıyor
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Sunumu PPTX dosyası olarak kaydediyor
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzdeyi, negatif değer ise puan cinsinden boyutu ifade eder. Kalıtım uygulanmaz. Okunup-yazılabilir float .

**Döndürür:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzdeyi, negatif değer ise puan cinsinden boyutu ifade eder. Kalıtım uygulanmaz. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz alanın yüzde olarak font boyutuna oranını belirtir. Negatif değer ise beyaz alanın puan cinsinden boyutunu belirtir. Okunup-yazılabilir float .

**Döndürür:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz alanın yüzde olarak font boyutuna oranını belirtir. Negatif değer ise beyaz alanın puan cinsinden boyutunu belirtir. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz alanın yüzde olarak font boyutuna oranını belirtir. Negatif değer ise beyaz alanın puan cinsinden boyutunu belirtir. Okunup-yazılabilir float .

**Döndürür:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz alanın yüzde olarak font boyutuna oranını belirtir. Negatif değer ise beyaz alanın puan cinsinden boyutunu belirtir. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunup-yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Kalıtım olmadan bir paragrafta sol kenar boşluğunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Döndürür:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Kalıtım olmadan bir paragrafta sol kenar boşluğunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Kalıtım olmadan bir paragrafta sağ kenar boşluğunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Döndürür:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Kalıtım olmadan bir paragrafta sağ kenar boşluğunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Kalıtım olmadan paragrafın İlk Satır Girintisini/Sarkan Girintisini döndürür veya ayarlar. Sarkan Girinti negatif değerlerle tanımlanabilir. Okunup-yazılabilir float .

**Döndürür:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Kalıtım olmadan paragrafın İlk Satır Girintisini/Sarkan Girintisini döndürür veya ayarlar. Sarkan Girinti negatif değerlerle tanımlanabilir. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Döndürür:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunup-yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ITabCollection](../../com.aspose.slides/itabcollection).

**Döndürür:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar. Okunup-yazılabilir [FontAlignment](../../com.aspose.slides/fontalignment).

**Döndürür:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar. Okunup-yazılabilir [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IPortionFormat](../../com.aspose.slides/iportionformat).

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunabilir long.

**Döndürür:**
long