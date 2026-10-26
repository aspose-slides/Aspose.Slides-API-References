---
title: IMathBox
second_title: Aspose.Slides Android için Java API Referansı
description: Matematiksel öğenin mantıksal kutulama paketlemesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathbox/
---
**Tüm Gerçekleştirilmiş Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Mantıksal kutulama (paketleme) işlemini matematiksel öğe için belirtir. Örneğin, bir kutulu nesne, hizalama noktasıyla ya da olmayan bir operatör emülatörü, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. Örneğin, “==” operatörü satır sonlarını önlemek için kutulanmalıdır.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metotlar

| Method | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatör Emülatörü. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatör Emülatörü. |
| [getNoBreak()](#getNoBreak--) | Kırılma yok. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Kırılma yok. |
| [getDifferential()](#getDifferential--) | Differansiyel. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differansiyel. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Doğru olduğunda, bu operatör emülatörü bir hizalama noktası görevi görür; yani diğer denklemlerdeki belirlenmiş hizalama noktaları ona göre hizalanabilir. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Doğru olduğunda, bu operatör emülatörü bir hizalama noktası görevi görür; yani diğer denklemlerdeki belirlenmiş hizalama noktaları ona göre hizalanabilir. |
| [getExplicitBreak()](#getExplicitBreak--) | Açık kırılma, Box nesnesinin başlangıcında satır sonu olup olmadığını belirler; böylece satır kutu nesnesinin başlangıcında kayar. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Açık kırılma, Box nesnesinin başlangıcında satır sonu olup olmadığını belirler; böylece satır kutu nesnesinin başlangıcında kayar. |
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


Operatör Emülatörü. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Emülatörleri, ‘==’ gibi bir veya daha fazla glifin bir operatör oluşturduğu durumlarda sıkça kullanılır. Varsayılan değer: false

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


Operatör Emülatörü. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Emülatörleri, ‘==’ gibi bir veya daha fazla glifin bir operatör oluşturduğu durumlarda sıkça kullanılır. Varsayılan değer: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


Kırılma yok. Bu özellik, nesne kutusundaki “kırılmaz” özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları meydana gelmez. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları gerçekleşebilir. Varsayılan: true

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


Kırılma yok. Bu özellik, nesne kutusundaki “kırılmaz” özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları meydana gelmez. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları gerçekleşebilir. Varsayılan: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


Differansiyel. Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

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


Differansiyel. Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. \\ud835\\udc51\\ud835\\udc65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

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
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


Doğru olduğunda, bu operatör emülatörü bir hizalama noktası görevi görür; yani diğer denklemlerdeki belirlenmiş hizalama noktaları ona göre hizalanabilir. Varsayılan: false

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


Doğru olduğunda, bu operatör emülatörü bir hizalama noktası görevi görür; yani diğer denklemlerdeki belirlenmiş hizalama noktaları ona göre hizalanabilir. Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


Açık kırılma, Box nesnesinin başlangıcında satır sonu olup olmadığını belirler; böylece satır kutu nesnesinin başlangıcında kayar. Önceki matematiksel satırdaki operatörün numarasını, mevcut satırdaki matematiksel metin için hizalama noktası olarak kullanılacak şekilde belirtir; olası değerler: 1..255 Varsayılan: 0 (açık kırılma yok)

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


Açık kırılma, Box nesnesinin başlangıcında satır sonu olup olmadığını belirler; böylece satır kutu nesnesinin başlangıcında kayar. Önceki matematiksel satırdaki operatörün numarasını, mevcut satırdaki matematiksel metin için hizalama noktası olarak kullanılacak şekilde belirtir; olası değerler: 1..255 Varsayılan: 0 (açık kırılma yok)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | byte |  |