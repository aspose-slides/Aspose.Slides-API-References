---
title: IMathMatrix
second_title: Aspose.Slides için Java API Referansı
description: Bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşan Matris nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathmatrix/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Matris nesnesini belirtir; çocuk öğeler bir veya daha fazla satır ve sütun içinde düzenlenir. Matrislerin yerleşik sınırlayıcıları olmadığını unutmamak gerekir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Boş argümanlar, matrislerde boşluk oluşturmak için kullanılabilir.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Matrisin öğeleri |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Matrisin öğeleri |
| [getRowCount()](#getRowCount--) | Matrisin satır sayısı |
| [getColumnCount()](#getColumnCount--) | Matrisin sütun sayısı |
| [getHidePlaceholders()](#getHidePlaceholders--) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [getBaseJustification()](#getBaseJustification--) | Etrafındaki metne göre dikey hizalamayı belirtir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Etrafındaki metne göre dikey hizalamayı belirtir. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Twip cinsinden minimum sütun genişliği (bir noktanın 1/20'i). Boşluk aralığı (\\u201cColumn Gap\\u201d ya da \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenerek toplam Matris Sütun Aralığı (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Twip cinsinden minimum sütun genişliği (bir noktanın 1/20'i). Boşluk aralığı (\\u201cColumn Gap\\u201d ya da \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenerek toplam Matris Sütun Aralığı (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. |
| [getColumnGapRule()](#getColumnGapRule--) | Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya nokta (twip olarak saklanır) olabilir. |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya nokta (twip olarak saklanır) olabilir. |
| [getColumnGap()](#getColumnGap--) | Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") ise birim 0.5 em artışı sayısı olarak yorumlanır. |
| [setColumnGap(long value)](#setColumnGap-long-) | Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") ise birim 0.5 em artışı sayısı olarak yorumlanır. |
| [getRowGapRule()](#getRowGapRule--) | Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. |
| [getRowGap()](#getRowGap--) | Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. |
| [setRowGap(long value)](#setRowGap-long-) | Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Belirtilen sütunun yatay hizalamasını al |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Belirtilen sütunun yatay hizalamasını ayarla |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Belirtilen sütunların yatay hizalamasını ayarla |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Belirtilen satırın arkasına yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Belirtilen satırı siler |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Belirtilen sütunun arkasına yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Belirtilen sütunu siler |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Matrisin öğeleri

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| row | int | Öğenin alınacağı satırın sıfır tabanlı indeksi |
| column | int | Öğenin alınacağı sütunun sıfır tabanlı indeksi |

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Matrisin öğeleri

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| row | int | Öğenin alınacağı satırın sıfır tabanlı indeksi |
| column | int | Öğenin alınacağı sütunun sıfır tabanlı indeksi |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Matrisin satır sayısı

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Döndürür:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Matrisin sütun sayısı

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Döndürür:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Boş matris öğeleri için yer tutucuları gizler Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Döndürür:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Boş matris öğeleri için yer tutucuları gizler Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Etrafındaki metne göre dikey hizalamayı belirtir. Olası değerler: top, bottom ve center. Varsayılan: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Döndürür:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Etrafındaki metne göre dikey hizalamayı belirtir. Olası değerler: top, bottom ve center. Varsayılan: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Twip cinsinden minimum sütun genişliği (bir noktanın 1/20'i). Boşluk aralığı (\\u201cColumn Gap\\u201d ya da \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenerek toplam Matris Sütun Aralığı (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Döndürür:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Twip cinsinden minimum sütun genişliği (bir noktanın 1/20'i). Boşluk aralığı (\\u201cColumn Gap\\u201d ya da \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenerek toplam Matris Sütun Aralığı (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Döndürür:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") ise birim 0.5 em artışı sayısı olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Döndürür:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") ise birim 0.5 em artışı sayısı olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Döndürür:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Döndürür:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Belirtilen sütunun yatay hizalamasını al

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfır tabanlı sütun indeksi |

**Döndürür:**
int - Belirtilen sütunun Yatay Hizalaması

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Belirtilen sütunun yatay hizalamasını ayarla

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfır tabanlı sütun indeksi |
| val | int | Belirtilen sütunun yeni yatay hizalama değeri |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Belirtilen sütunların yatay hizalamasını ayarla

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Hizalama ayarlanacak ilk sütunun sıfır tabanlı indeksi |
| columnsCount | long | Hizalama belirtilecek sütun sayısı |
| val | int | Belirtilen sütunların yeni yatay hizalama değeri |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | int | Yeni bir satır eklenmeden önceki satırın indeksi |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Belirtilen satırın arkasına yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | int | Yeni bir satır eklenmeden sonraki satırın indeksi |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Belirtilen satırı siler

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | int | Silinecek satırın sıfır tabanlı indeksi |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Yeni bir sütun eklenmeden önceki sütunun indeksi |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Belirtilen sütunun arkasına yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Yeni bir sütun eklenmeden sonraki sütunun indeksi |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Belirtilen sütunu siler

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Silinecek sütunun sıfır tabanlı indeksi |