---
title: MathBox
second_title: Aspose.Slides için Java API Referansı
description: Matematiksel öğenin mantıksal kutulama paketlenmesini belirtir.
type: docs
url: /tr/com.aspose.slides/mathbox/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Matematiksel öğenin mantıksal kutulanmasını (paketlenmesini) belirtir. Örneğin, kutulu bir nesne bir hizalama noktasıyla veya hizalama noktasız bir operatör taklitçisi olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. Örneğin, "==" operatörü satır sonlarını önlemek için kutulanmalıdır.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | MathBox'ı belirtilen öğeyle bir argüman olarak başlatır |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatör Taklitçisi. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatör Taklitçisi. |
| [getNoBreak()](#getNoBreak--) | Kesintisiz Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Kesintisiz Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. |
| [getDifferential()](#getDifferential--) | Diferansiyel Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay aralığı alır. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferansiyel Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay aralığı alır. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası olarak hizmet eder; yani, diğer denklemlerde belirlenmiş hizalama noktaları onunla hizalanabilir. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası olarak hizmet eder; yani, diğer denklemlerde belirlenmiş hizalama noktaları onunla hizalanabilir. |
| [getExplicitBreak()](#getExplicitBreak--) | Açık kesinti, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır, kutu nesnesinin başlangıcında kayar. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Açık kesinti, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır, kutu nesnesinin başlangıcında kayar. |
| [getChildren()](#getChildren--) | Çocuk öğeleri alır |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakter Özellikleri |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

MathBox'ı belirtilen öğeyle bir argüman olarak başlatır

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Kutu uygulanan temel öğe. Null olabilir. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```


**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operatör Taklitçisi. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini miras alır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Taklitçileri, bir veya daha fazla glifin '==' gibi bir operatör oluşturduğu durumlarda sıklıkla kullanılır. Varsayılan değer: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Döndürür:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operatör Taklitçisi. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini miras alır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Taklitçileri, bir veya daha fazla glifin '==' gibi bir operatör oluşturduğu durumlarda sıklıkla kullanılır. Varsayılan değer: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Kesintisiz Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör taklitçileri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde kesintiler oluşabilir. Varsayılan: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Döndürür:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Kesintisiz Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör taklitçileri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde kesintiler oluşabilir. Varsayılan: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Diferansiyel Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay aralığı alır. Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Döndürür:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Diferansiyel Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay aralığı alır. Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenmiş hizalama noktaları onunla hizalanabilir. Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Döndürür:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenmiş hizalama noktaları onunla hizalanabilir. Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Açık kesinti, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır, kutu nesnesinin başlangıcında kayar. Bir önceki matematik metni satırındaki operatörün sayısını belirtir; bu sayı, mevcut matematik metni satırı için hizalama noktası olarak kullanılacaktır. Olası değerler: 1..255 Varsayılan: 0 (açık kesinti yok)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Döndürür:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Açık kesinti, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler; böylece satır, kutu nesnesinin başlangıcında kayar. Bir önceki matematik metni satırındaki operatörün sayısını belirtir; bu sayı, mevcut matematik metni satırı için hizalama noktası olarak kullanılacaktır. Olası değerler: 1..255 Varsayılan: 0 (açık kesinti yok)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Çocuk öğeleri alır

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakter Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps