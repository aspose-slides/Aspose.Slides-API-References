---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng bất biến chứa các thuộc tính lược đồ định dạng hiệu lực.
type: docs
url: /vi/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Đối tượng bất biến chứa các thuộc tính lược đồ định dạng hiệu lực.

--------------------

Giao diện này được sử dụng như một phần của [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillStyles(Integer styleColor)](#getFillStyles-java.lang.Integer-) | Trả về một bộ sưu tập các kiểu tô màu được định nghĩa bởi theme. |
| [getLineStyles(Integer styleColor)](#getLineStyles-java.lang.Integer-) | Trả về một bộ sưu tập các kiểu đường được định nghĩa bởi theme. |
| [getEffectStyles(Integer styleColor)](#getEffectStyles-java.lang.Integer-) | Trả về một bộ sưu tập các kiểu hiệu ứng được định nghĩa bởi theme. |
| [getBackgroundFillStyles(Integer styleColor)](#getBackgroundFillStyles-java.lang.Integer-) | Trả về một bộ sưu tập các kiểu nền được định nghĩa bởi theme. |

### getFillStyles(Integer styleColor) {#getFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Integer styleColor)
```

Trả về một bộ sưu tập các kiểu tô màu được định nghĩa bởi theme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | Màu java.lang.Integer |

**Trả về:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Bộ sưu tập các định dạng tô đầy hiệu lực [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)

### getLineStyles(Integer styleColor) {#getLineStyles-java.lang.Integer-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Integer styleColor)
```

Trả về một bộ sưu tập các kiểu đường được định nghĩa bởi theme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | Màu java.lang.Integer |

**Trả về:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Bộ sưu tập các định dạng đường hiệu lực [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)

### getEffectStyles(Integer styleColor) {#getEffectStyles-java.lang.Integer-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Integer styleColor)
```

Trả về một bộ sưu tập các kiểu hiệu ứng được định nghĩa bởi theme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | Màu java.lang.Integer |

**Trả về:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Bộ sưu tập các định dạng hiệu ứng hiệu lực [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)

### getBackgroundFillStyles(Integer styleColor) {#getBackgroundFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Integer styleColor)
```

Trả về một bộ sưu tập các kiểu nền được định nghĩa bởi theme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | Màu java.lang.Integer |

**Trả về:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Bộ sưu tập các định dạng nền hiệu lực [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)