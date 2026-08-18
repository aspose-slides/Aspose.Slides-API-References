---
title: IMathBox
second_title: Aspose.Slides için Java API Referansı
description: Matematiksel öğenin mantıksal kutulama paketlemesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathbox/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Matematiksel öğenin mantıksal kutulanmasını (paketlenmesini) belirtir. Örneğin, kutulanmış bir nesne, hizalama noktasıyla birlikte ya da olmadan bir operatör öykünücüsü olarak, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarının içinde bulunmasını engelleyecek şekilde gruplanabilir. Örneğin, “==” operatörünün satır sonlarını önlemek için kutulanması gerekir.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatör Öykünücüsü. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatör Öykünücüsü. |
| [getNoBreak()](#getNoBreak--) | Kesinti yok. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Kesinti yok. |
| [getDifferential()](#getDifferential--) | Differansial. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differansial. |
| [getAlignmentPoint()](#getAlignmentPoint--) | True olduğunda, bu operatör öykünücüsü bir hizalama noktası görevi görür; yani diğer denklemlerde belirtilen hizalama noktaları onunla hizalanabilir. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | True olduğunda, bu operatör öykünücüsü bir hizalama noktası görevi görür; yani diğer denklemlerde belirtilen hizalama noktaları onunla hizalanabilir. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başlangıcında sarar. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başlangıcında sarar. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operatör Öykünücüsü. True olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Öykünücüleri, genellikle bir veya daha fazla glifin ‘==’ gibi bir operatör oluşturmak için birleştirildiği durumlarda kullanılır. Varsayılan değer: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Döndürür:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operatör Öykünücüsü. True olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Öykünücüleri, genellikle bir veya daha fazla glifin ‘==’ gibi bir operatör oluşturmak için birleştirildiği durumlarda kullanılır. Varsayılan değer: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Kesinti yok. Bu özellik, nesne kutusundaki “kesilemez” özelliğini belirtir. True olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör öykünücüleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Varsayılan: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Döndürür:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Kesinti yok. Bu özellik, nesne kutusundaki “kesilemez” özelliğini belirtir. True olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör öykünücüleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Varsayılan: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differansial. True olduğunda, kutu bir differansial gibi davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel differansial için uygun yatay boşluğu alır. Varsayılan: false

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
public abstract void setDifferential(boolean value)
```

Differansial. True olduğunda, kutu bir differansial gibi davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel differansial için uygun yatay boşluğu alır. Varsayılan: false

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
public abstract boolean getAlignmentPoint()
```

True olduğunda, bu operatör öykünücüsü bir hizalama noktası görevi görür; yani diğer denklemlerde belirtilen hizalama noktaları onunla hizalanabilir. Varsayılan: false

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
public abstract void setAlignmentPoint(boolean value)
```

True olduğunda, bu operatör öykünücüsü bir hizalama noktası görevi görür; yani diğer denklemlerde belirtilen hizalama noktaları onunla hizalanabilir. Varsayılan: false

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
public abstract byte getExplicitBreak()
```

Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başlangıcında sarar. Önceki satırdaki matematiksel metnin operatör numarasını belirler; bu numara, mevcut satırdaki matematiksel metnin hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (explicit break yok)

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
public abstract void setExplicitBreak(byte value)
```

Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır, kutu nesnesinin başlangıcında sarar. Önceki satırdaki matematiksel metnin operatör numarasını belirler; bu numara, mevcut satırdaki matematiksel metnin hizalama noktası olarak kullanılır. Olası değerler: 1..255 Varsayılan: 0 (explicit break yok)

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