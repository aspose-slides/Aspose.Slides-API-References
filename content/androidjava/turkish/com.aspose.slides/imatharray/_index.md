---
title: IMathArray
second_title: Aspose.Slides for Android için Java API Referansı
description: Denklemler veya herhangi bir matematiksel nesnenin dikey bir dizisini belirtir
type: docs
url: /tr/com.aspose.slides/imatharray/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Dikey bir dizi denklem ya da herhangi bir matematiksel nesneyi belirtir

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | Dizinin öğe kümesi |
| [getBaseJustification()](#getBaseJustification--) | Dizinin çevre metne göre hizalanmasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Dizinin çevre metne göre hizalanmasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maksimum Dağıtım: Doğru olduğunda, dizi içeren öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yayılır. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maksimum Dağıtım: Doğru olduğunda, dizi içeren öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yayılır. |
| [getObjectDistribution()](#getObjectDistribution--) | Nesne Dağıtımı: Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yayılır. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Nesne Dağıtımı: Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yayılır. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Dizi öğeleri arasındaki dikey boşluk türü |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Dizi öğeleri arasındaki dikey boşluk türü |
| [getRowSpacing()](#getRowSpacing--) | Dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan (Exactly) veya yarım satır (Multiple) olur. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan (Exactly) veya yarım satır (Multiple) olur. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Dizinin öğe kümesi

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Döndürür:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Dizinin çevre metne göre hizalanmasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. Varsayılan değer: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Döndürür:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Dizinin çevre metne göre hizalanmasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. Varsayılan değer: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Maksimum Dağıtım: Doğru olduğunda, dizi içeren öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yayılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Döndürür:**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maksimum Dağıtım: Doğru olduğunda, dizi içeren öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yayılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Nesne Dağıtımı: Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yayılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Döndürür:**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Nesne Dağıtımı: Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yayılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Dizi öğeleri arasındaki dikey boşluk türü

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Döndürür:**
int

### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Dizi öğeleri arasındaki dikey boşluk türü

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan (Exactly) veya yarım satır (Multiple) olur. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Döndürür:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan (Exactly) veya yarım satır (Multiple) olur. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |