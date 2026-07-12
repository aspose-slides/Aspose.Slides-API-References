---
title: MathMatrix
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşan Matrix nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/mathmatrix/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşan bir nesne olarak tanımlar. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matrisleri köşeli parantez içine yerleştirmek için sınırlayıcı nesneyi (IMathDelimiter) kullanmalısınız. Null argümanları, matrislerde boşluk oluşturmak için kullanılabilir.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRowCount()](#getRowCount--) | Matrisdeki satır sayısı |
| [getColumnCount()](#getColumnCount--) | Matrisdeki sütun sayısı |
| [getHidePlaceholders()](#getHidePlaceholders--) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [getBaseJustification()](#getBaseJustification--) | Çevredeki metne göre dikey hizalamayı belirtir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Çevredeki metne göre dikey hizalamayı belirtir. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum sütun genişliği twip cinsinden (bir noktanın 1/20'si). Boşluk aralığı (\\u201cColumn Gap\\u201d veya \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenir ve toplam Matris Sütun Aralığını (farklı sütunların aynı kenarları arasındaki mesafe) belirler. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum sütun genişliği twip cinsinden (bir noktanın 1/20'si). Boşluk aralığı (\\u201cColumn Gap\\u201d veya \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenir ve toplam Matris Sütun Aralığını (farklı sütunların aynı kenarları arasındaki mesafe) belirler. |
| [getColumnGapRule()](#getColumnGapRule--) | Matris sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya noktalar (twip olarak saklanır) olabilir. |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Matris sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya noktalar (twip olarak saklanır) olabilir. |
| [getColumnGap()](#getColumnGap--) | Matris sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ("Multiple") ise birim 0.5 em artışının sayısı olarak yorumlanır. |
| [setColumnGap(long value)](#setColumnGap-long-) | Matris sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ("Multiple") ise birim 0.5 em artışının sayısı olarak yorumlanır. |
| [getRowGapRule()](#getRowGapRule--) | Matris satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya noktalar (twip olarak saklanır) olabilir. |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Matris satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya noktalar (twip olarak saklanır) olabilir. |
| [getRowGap()](#getRowGap--) | Matris satırları arasındaki dikey boşluğun değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 ("Multiple") ise birim yarım satır olarak yorumlanır. |
| [setRowGap(long value)](#setRowGap-long-) | Matris satırları arasındaki dikey boşluğun değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 ("Multiple") ise birim yarım satır olarak yorumlanır. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Matris öğesi |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Matris öğesi |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Belirtilen sütunun yatay hizalamasını al |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Belirtilen sütunun yatay hizalamasını ayarla |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Belirtilen sütunların yatay hizalamasını ayarla |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Belirtilen satırdan önce yeni bir satır ekle. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Belirtilen satırdan sonra yeni bir satır ekle. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Belirtilen satırı siler. |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Belirtilen sütundan önce yeni bir sütun ekle. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Belirtilen sütundan sonra yeni bir sütun ekle. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Belirtilen sütunu siler. |
| [getChildren()](#getChildren--) | Çocuk öğeleri al. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowCount | int | satır sayısı |
| columnCount | int | sütun sayısı |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Matrisdeki satır sayısı

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Dönen Değer:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Matrisdeki sütun sayısı

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Dönen Değer:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Boş matris öğeleri için yer tutucuları gizler Varsayılan: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Dönen Değer:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
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
public final int getBaseJustification()
```

Çevredeki metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center. Varsayılan: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Dönen Değer:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Çevredeki metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center. Varsayılan: Center

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
public final long getMinColumnWidth()
```

Minimum sütun genişliği twip cinsinden (bir noktanın 1/20'si). Boşluk aralığı (\\u201cColumn Gap\\u201d veya \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenir ve toplam Matris Sütun Aralığını (farklı sütunların aynı kenarları arasındaki mesafe) belirler. Varsayılan: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Dönen Değer:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Minimum sütun genişliği twip cinsinden (bir noktanın 1/20'si). Boşluk aralığı (\\u201cColumn Gap\\u201d veya \\u201cGap Width\\u201d olarak da adlandırılır) MinColumnWidth'e eklenir ve toplam Matris Sütun Aralığını (farklı sütunların aynı kenarları arasındaki mesafe) belirler. Varsayılan: 0.

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
public final int getColumnGapRule()
```

Matris sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya noktalar (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Dönen Değer:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Matris sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya noktalar (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Matris sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ("Multiple") ise birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Dönen Değer:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Matris sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ("Multiple") ise birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

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
public final int getRowGapRule()
```

Matris satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya noktalar (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Dönen Değer:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Matris satırları arasındaki dikey boşluk tipi; Dikey boşluk birimleri satır veya noktalar (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

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
public final long getRowGap()
```

Matris satırları arasındaki dikey boşluğun değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 ("Multiple") ise birim yarım satır olarak yorumlanır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Dönen Değer:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Matris satırları arasındaki dikey boşluğun değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 ("Multiple") ise birim yarım satır olarak yorumlanır. Varsayılan: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Matris öğesi

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
| row | int | Alınacak öğenin sıfır tabanlı satır indeksi |
| column | int | Alınacak öğenin sıfır tabanlı sütun indeksi |

**Dönen Değer:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Matris öğesi

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
| row | int | Alınacak öğenin sıfır tabanlı satır indeksi |
| column | int | Alınacak öğenin sıfır tabanlı sütun indeksi |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Dönen Değer:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Belirtilen sütunun yatay hizalamasını al

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfır tabanlı sütun indeksi |

**Dönen Değer:**
int - Belirtilen sütunun Yatay Hizalaması
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Belirtilen sütunun yatay hizalamasını ayarla

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int | Sıfır tabanlı sütun indeksi |
| val | int | Belirtilen sütunun yeni yatay hizalama değeri |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
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
| columnsCount | long | Hizalamanın uygulanacağı sütun sayısı |
| val | int | Belirtilen sütunların yeni yatay hizalama değeri |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Belirtilen satırdan önce yeni bir satır ekle. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | int | Yeni satırın ekleneceği satırın indeksi |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Belirtilen satırdan sonra yeni bir satır ekle. Yeni satırdaki tüm öğeler başlangıçta null olur.

--------------------

> ```
> Örnek:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | int | Silinecek satırın sıfır tabanlı indeksi. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Belirtilen sütundan önce yeni bir sütun ekle. Yeni sütundaki tüm öğeler başlangıçta null olur.

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
| columnIndex | int | Yeni sütunun ekleneceği sütunun indeksi |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Belirtilen sütundan sonra yeni bir sütun ekle. Yeni sütundaki tüm öğeler başlangıçta null olur.

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
| columnIndex | int | Yeni sütunun ekleneceği sütunun indeksi |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
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
| columnIndex | int | Silinecek sütunun sıfır tabanlı indeksi. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Çocuk öğeleri al

**Dönen Değer:**
com.aspose.slides.IMathElement[]