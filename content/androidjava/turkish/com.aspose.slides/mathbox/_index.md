---
title: MathBox
second_title: Aspose.Slides for Android, Java API Referansı üzerinden
description: Matematiksel öğenin mantıksal kutulama paketlemesini belirtir.
type: docs
url: /tr/com.aspose.slides/mathbox/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Mantıksal kutulama (paketleme) işlemini matematiksel öğe için belirtir. Örneğin, kutulanmış bir nesne hizalama noktasıyla ya da hizalama noktası olmadan bir operatör taklitçisi olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarının içinde yer almasına izin vermeyecek şekilde gruplandırılabilir. Örneğin, "==" operatörü satır sonlarını önlemek için kutulanmalıdır.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Belirtilen öğeyi argüman olarak kullanarak MathBox'ı başlatır |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatör Taklitçisi. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatör Taklitçisi. |
| [getNoBreak()](#getNoBreak--) | Kırılma yok Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Kırılma yok Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirtir. |
| [getDifferential()](#getDifferential--) | Diferansiyel Doğru olduğunda, kutu bir diferansiyel gibi davranır (ör., \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferansiyel Doğru olduğunda, kutu bir diferansiyel gibi davranır (ör., \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. |
| [getExplicitBreak()](#getExplicitBreak--) | Açık satır sonu, Box nesnesinin başında bir satır sonu olup olmadığını belirtir, böylece satır kutunun başında kayar. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Açık satır sonu, Box nesnesinin başında bir satır sonu olup olmadığını belirtir, böylece satır kutunun başında kayar. |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Belirtilen öğeyi argüman olarak kullanarak MathBox'ı başlatır

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Kutuya uygulanan temel öğe. Null olabilir. |

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

Operatör Taklitçisi. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operatör Taklitçileri, bir veya daha fazla glif bir araya gelerek bir operatör oluşturduğunda sıklıkla kullanılır, örneğin '=='. Varsayılan değer: false

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

Operatör Taklitçisi. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operatör Taklitçileri, bir veya daha fazla glif bir araya gelerek bir operatör oluşturduğunda sıklıkla kullanılır, örneğin '=='. Varsayılan değer: false

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

Kırılma yok Bu özellik nesne kutusundaki "unbreakable" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşmaz. Bu, birden fazla ikili operatörden oluşan operatör taklitçileri için önemli olabilir. Bu öğe belirtilmezse, kutu içinde satır sonları oluşabilir. Varsayılan: true

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

Kırılma yok Bu özellik nesne kutusundaki "unbreakable" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşmaz. Bu, birden fazla ikili operatörden oluşan operatör taklitçileri için önemli olabilir. Bu öğe belirtilmezse, kutu içinde satır sonları oluşabilir. Varsayılan: true

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

Diferansiyel Doğru olduğunda, kutu bir diferansiyel gibi davranır (ör., \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

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

Diferansiyel Doğru olduğunda, kutu bir diferansiyel gibi davranır (ör., \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

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

Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. Varsayılan: false

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

Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası görevi görür; yani, diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. Varsayılan: false

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

Açık satır sonu, Box nesnesinin başında bir satır sonu olup olmadığını belirtir, böylece satır kutunun başında kayar. Önceki satırdaki matematiksel metnin operatör sayısını belirler; bu sayı, mevcut satırdaki matematiksel metnin hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (açık satır sonu yok)

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

Açık satır sonu, Box nesnesinin başında bir satır sonu olup olmadığını belirtir, böylece satır kutunun başında kayar. Önceki satırdaki matematiksel metnin operatör sayısını belirler; bu sayı, mevcut satırdaki matematiksel metnin hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (açık satır sonu yok)

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

Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps