---
title: MathMatrix
second_title: Aspose.Slides Java API Referansı
description: Bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşan Matrix nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/mathmatrix/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Matrix nesnesini belirtir; bu nesne bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşur. Matrislerin yerleşik ayraçları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için ayraç nesnesini (IMathDelimiter) kullanmalısınız. Null argümanlar, matrislerde boşluk oluşturmak için kullanılabilir.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | MathMatrix sınıfının yeni bir örneğini başlatır. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getRowCount()](#getRowCount--) | Matrisin satır sayısı |
| [getColumnCount()](#getColumnCount--) | Matrisin sütun sayısı |
| [getHidePlaceholders()](#getHidePlaceholders--) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [getBaseJustification()](#getBaseJustification--) | Çevre metne göre dikey hizalamayı belirtir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Çevre metne göre dikey hizalamayı belirtir. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Twip cinsinden minimum sütun genişliği (1/20 nokta). Boşluk aralığı (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) MinColumnWidth'e eklenerek toplam Matrix Column Spacing (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Twip cinsinden minimum sütun genişliği (1/20 nokta). Boşluk aralığı (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) MinColumnWidth'e eklenerek toplam Matrix Column Spacing (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. |
| [getColumnGapRule()](#getColumnGapRule--) | Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. |
| [getColumnGap()](#getColumnGap--) | Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. ColumnGapRule 4 ('Multiple') olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. |
| [setColumnGap(long value)](#setColumnGap-long-) | Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. ColumnGapRule 4 ('Multiple') olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. |
| [getRowGapRule()](#getRowGapRule--) | Bir matrisin satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya puan (twip olarak saklanır) olabilir. |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Bir matrisin satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya puan (twip olarak saklanır) olabilir. |
| [getRowGap()](#getRowGap--) | Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. RowGapRule 4 ('Multiple') olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. |
| [setRowGap(long value)](#setRowGap-long-) | Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. RowGapRule 4 ('Multiple') olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Matris öğesi |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Matris öğesi |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakter Özellikleri |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Belirtilen sütunun yatay hizalamasını alır |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Belirtilen sütunun yatay hizalamasını ayarlar |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Belirtilen sütunların yatay hizalamasını ayarlar |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Belirtilen satırı siler |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Belirtilen sütunun sonrasına yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Belirtilen sütunu siler |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

MathMatrix sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rowCount | int | satır sayısı |
| columnCount | int | sütun sayısı |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Boş matris öğeleri için yer tutucuları gizler Varsayılan: false

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Döndürür:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Boş matris öğeleri için yer tutucuları gizler Varsayılan: false

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Çevre metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center. Varsayılan: Center

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Döndürür:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Çevre metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center. Varsayılan: Center

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Twip cinsinden minimum sütun genişliği (1/20 nokta). Boşluk aralığı (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) MinColumnWidth'e eklenerek toplam Matrix Column Spacing (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Döndürür:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Twip cinsinden minimum sütun genişliği (1/20 nokta). Boşluk aralığı (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) MinColumnWidth'e eklenerek toplam Matrix Column Spacing (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Döndürür:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. ColumnGapRule 4 ('Multiple') olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**Döndürür:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. ColumnGapRule 4 ('Multiple') olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Bir matrisin satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Döndürür:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Bir matrisin satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. RowGapRule 4 ('Multiple') olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. Varsayılan: 0

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Döndürür:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ('Exactly') olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır. RowGapRule 4 ('Multiple') olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. Varsayılan: 0

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Matris öğesi

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| row | int | Öğeyi almak için satırın sıfırdan başlayan dizini |
| column | int | Öğeyi almak için sütunun sıfırdan başlayan dizini |

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Matris öğesi

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| row | int | Öğeyi almak için satırın sıfırdan başlayan dizini |
| column | int | Öğeyi almak için sütunun sıfırdan başlayan dizini |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakter Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Belirtilen sütunun yatay hizalamasını alır

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfırdan başlayan sütun indeksi |

**Döndürür:**
int - Belirtilen sütunun Yatay Hizalaması
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Belirtilen sütunun yatay hizalamasını ayarlar

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfırdan başlayan sütun indeksi |
| val | int | Belirtilen sütunun yeni yatay hizalama değeri |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Belirtilen sütunların yatay hizalamasını ayarlar

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Hizalama ayarlanacak ilk sütunun sıfırdan başlayan indeksi |
| columnsCount | long | Hizalama yapılacak sütun sayısı |
| val | int | Belirtilen sütunun yeni yatay hizalama değeri |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rowIndex | int | Yeni satırın ekleneceği satırın indeksi |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rowIndex | int | Yeni satırın ekleneceği satırın indeksi |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Belirtilen satırı siler

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rowIndex | int | Silinecek satırın sıfırdan başlayan indeksi |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Yeni sütunun ekleneceği sütunun indeksi |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Belirtilen sütunun sonrasına yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Yeni sütunun ekleneceği sütunun indeksi |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Belirtilen sütunu siler

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| columnIndex | int | Silinecek sütunun sıfırdan başlayan indeksi |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]