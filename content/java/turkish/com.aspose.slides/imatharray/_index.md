---
title: IMathArray
second_title: Aspose.Slides Java için API Referansı
description: Denklemler veya herhangi bir matematiksel nesnenin dikey bir dizisini belirtir
type: docs
url: /tr/com.aspose.slides/imatharray/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Denklemler veya herhangi bir matematiksel nesnenin dikey dizisini belirtir

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | Dizinin öğelerinin kümesi |
| [getBaseJustification()](#getBaseJustification--) | Dizinin, çevredeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya ortasına hizalanabilir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Dizinin, çevredeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya ortasına hizalanabilir. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maksimum Dağıtım. True olduğunda, dizi, içerdiği öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre boşluklandırılır. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maksimum Dağıtım. True olduğunda, dizi, içerdiği öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre boşluklandırılır. |
| [getObjectDistribution()](#getObjectDistribution--) | Nesne Dağıtımı. True olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre boşluklandırılır. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Nesne Dağıtımı. True olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre boşluklandırılır. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Dizi elemanları arasındaki dikey boşluk türü |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Dizi elemanları arasındaki dikey boşluk türü |
| [getRowSpacing()](#getRowSpacing--) | Dizi satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple ise ölçü birimi half-lines olur. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Dizi satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple ise ölçü birimi half-lines olur. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Dizinin öğelerinin kümesi

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

Dizinin, çevredeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya ortasına hizalanabilir. Varsayılan değer: Center

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

Dizinin, çevredeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya ortasına hizalanabilir. Varsayılan değer: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Maksimum Dağıtım. True olduğunda, dizi, içerdiği öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre boşluklandırılır.

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

Maksimum Dağıtım. True olduğunda, dizi, içerdiği öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre boşluklandırılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Nesne Dağıtımı. True olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre boşluklandırılır.

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

Nesne Dağıtımı. True olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre boşluklandırılır.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Dizi elemanları arasındaki dikey boşluk türü

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

Dizi elemanları arasındaki dikey boşluk türü

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Dizi satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple ise ölçü birimi half-lines olur. Varsayılan: 0

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

Dizi satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple ise ölçü birimi half-lines olur. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |