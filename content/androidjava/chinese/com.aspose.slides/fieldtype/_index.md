---
title: FieldType
second_title: Aspose.Slides 针对 Android 的 Java API 参考
description: 表示字段的类型。
type: docs
url: /zh/com.aspose.slides/fieldtype/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)  
```
public final class FieldType implements IFieldType
```

表示字段的类型。当字段更新时，该值决定将哪个文本设置到字段部分。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | 初始化 FieldType 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInternalString()](#getInternalString--) | 返回此 FieldType 对象的内部名称。 |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | 返回此 FieldType 对象的内部名称。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查此字段是否等于另一个字段。 |
| [hashCode()](#hashCode--) | 返回此对象的哈希码。 |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 检查两个 FieldType 对象是否相等。 |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 检查两个 FieldType 对象是否不相等。 |
| [getSlideNumber()](#getSlideNumber--) | 当前幻灯片的编号。 |
| [getFooter()](#getFooter--) | 幻灯片的页脚。 |
| [getHeader()](#getHeader--) | 幻灯片的页眉。 |
| [getDateTime()](#getDateTime--) | 渲染应用程序默认日期时间格式的当前日期和时间。 |
| [getDateTime1()](#getDateTime1--) | 第一次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY）。 |
| [getDateTime2()](#getDateTime2--) | 第二次预定义格式的当前日期和时间（英文格式 Day, Month DD, YYYY）。 |
| [getDateTime3()](#getDateTime3--) | 第三次预定义格式的当前日期和时间（英文格式 DD Month YYYY）。 |
| [getDateTime4()](#getDateTime4--) | 第四次预定义格式的当前日期和时间（英文格式 Month DD, YYYY）。 |
| [getDateTime5()](#getDateTime5--) | 第五次预定义格式的当前日期和时间（英文格式 DD-Mon-YY）。 |
| [getDateTime6()](#getDateTime6--) | 第六次预定义格式的当前日期和时间（英文格式 Month YY）。 |
| [getDateTime7()](#getDateTime7--) | 第七次预定义格式的当前日期和时间（英文格式 Mon-YY）。 |
| [getDateTime8()](#getDateTime8--) | 第八次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY hh:mm AM/PM）。 |
| [getDateTime9()](#getDateTime9--) | 第九次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY hh:mm:ss AM/PM）。 |
| [getDateTime10()](#getDateTime10--) | 第十次预定义格式的当前日期和时间（英文格式 hh:mm）。 |
| [getDateTime11()](#getDateTime11--) | 第十一次预定义格式的当前日期和时间（英文格式 hh:mm:ss）。 |
| [getDateTime12()](#getDateTime12--) | 第十二次预定义格式的当前日期和时间（英文格式 hh:mm AM/PM）。 |
| [getDateTime13()](#getDateTime13--) | 第十三次预定义格式的当前日期和时间（英文格式 hh:mm:ss AM/PM）。 |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

初始化 FieldType 类的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

返回此 FieldType 对象的内部名称。 读/写 String。

**返回:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

返回此 FieldType 对象的内部名称。 读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

检查此字段是否等于另一个字段。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的字段。 |

**返回:**
boolean - 如果字段相等则为 True。

### hashCode() {#hashCode--}
```
public int hashCode()
```

返回此对象的哈希码。

**返回:**
int - 哈希码。

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

检查两个 FieldType 对象是否相等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 第一个要比较的 FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 第二个要比较的 FieldType。 |

**返回:**
boolean - 如果 FieldType 对象相等则为 True。

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

检查两个 FieldType 对象是否不相等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 第一个要比较的 FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 第二个要比较的 FieldType。 |

**返回:**
boolean - 如果 FieldType 对象不相等则为 True。

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

当前幻灯片的编号。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

幻灯片的页脚。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

幻灯片的页眉。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

渲染应用程序默认日期时间格式的当前日期和时间。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

第一次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

第二次预定义格式的当前日期和时间（英文格式 Day, Month DD, YYYY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

第三次预定义格式的当前日期和时间（英文格式 DD Month YYYY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

第四次预定义格式的当前日期和时间（英文格式 Month DD, YYYY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

第五次预定义格式的当前日期和时间（英文格式 DD-Mon-YY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

第六次预定义格式的当前日期和时间（英文格式 Month YY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldName getDateTime7()
```

第七次预定义格式的当前日期和时间（英文格式 Mon-YY）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

第八次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY hh:mm AM/PM）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

第九次预定义格式的当前日期和时间（英文格式 MM/DD/YYYY hh:mm:ss AM/PM）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

第十次预定义格式的当前日期和时间（英文格式 hh:mm）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

第十一次预定义格式的当前日期和时间（英文格式 hh:mm:ss）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

第十二次预定义格式的当前日期和时间（英文格式 hh:mm AM/PM）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

第十三次预定义格式的当前日期和时间（英文格式 hh:mm:ss AM/PM）。 只读 [FieldType](../../com.aspose.slides/fieldtype)。

**返回:**
[FieldType](../../com.aspose.slides/fieldtype)