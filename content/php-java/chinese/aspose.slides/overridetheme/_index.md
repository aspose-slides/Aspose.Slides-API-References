---
title: OverrideTheme
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/overridetheme/
---
## OverrideTheme 类

表示一个覆盖主题。

### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 将 ColorScheme、FontScheme、FormatScheme 设置为 null，以禁用使用此主题对象的任何覆盖。 |

**返回：**
void


---

### getColorScheme {#getColorScheme}

| 名称 | 描述 |
| --- | --- |
| getColorScheme () | 返回颜色方案。只读 IColorScheme。 |

**返回：**
[ColorScheme](../colorscheme)


---

### getFontScheme {#getFontScheme}

| 名称 | 描述 |
| --- | --- |
| getFontScheme () | 返回字体方案。只读 IFontScheme。 |

**返回：**
[FontScheme](../fontscheme)


---

### getFormatScheme {#getFormatScheme}

| 名称 | 描述 |
| --- | --- |
| getFormatScheme () | 返回形状格式方案。只读 IFormatScheme。 |

**返回：**
[FormatScheme](../formatscheme)


---

### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

**返回：**
long


---

### initColorScheme {#initColorScheme}

| 名称 | 描述 |
| --- | --- |
| initColorScheme () | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 ColorScheme 已经初始化（非 null），则抛出。 |


---

### initColorSchemeFrom {#initColorSchemeFrom}

| 名称 | 描述 |
| --- | --- |
| initColorSchemeFrom ([ColorScheme](../colorscheme)) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| colorScheme | [ColorScheme](../colorscheme) | 用于初始化的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentNullException | 如果 colorScheme 参数为 null，则抛出。 |


---

### initColorSchemeFromInherited {#initColorSchemeFromInherited}

| 名称 | 描述 |
| --- | --- |
| initColorSchemeFromInherited () | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。并使用 InheritedTheme 的 ColorScheme 数据来初始化此新对象的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 ColorScheme 已经初始化（非 null），则抛出。 |


---

### initFontScheme {#initFontScheme}

| 名称 | 描述 |
| --- | --- |
| initFontScheme () | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 FontScheme 已经初始化（非 null），则抛出。 |


---

### initFontSchemeFrom {#initFontSchemeFrom}

| 名称 | 描述 |
| --- | --- |
| initFontSchemeFrom ([FontScheme](../fontscheme)) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontScheme | [FontScheme](../fontscheme) | 用于初始化的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentNullException | 如果 fontScheme 参数为 null，则抛出。 |


---

### initFontSchemeFromInherited {#initFontSchemeFromInherited}

| 名称 | 描述 |
| --- | --- |
| initFontSchemeFromInherited () | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。并使用 InheritedTheme 的 FontScheme 数据来初始化此新对象的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 FontScheme 已经初始化（非 null），则抛出。 |


---

### initFormatScheme {#initFormatScheme}

| 名称 | 描述 |
| --- | --- |
| initFormatScheme () | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 FormatScheme 已经初始化（非 null），则抛出。 |


---

### initFormatSchemeFrom {#initFormatSchemeFrom}

| 名称 | 描述 |
| --- | --- |
| initFormatSchemeFrom ([FormatScheme](../formatscheme)) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| formatScheme | [FormatScheme](../formatscheme) | 用于初始化的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentNullException | 如果 formatScheme 参数为 null，则抛出。 |


---

### initFormatSchemeFromInherited {#initFormatSchemeFromInherited}

| 名称 | 描述 |
| --- | --- |
| initFormatSchemeFromInherited () | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。并使用 InheritedTheme 的 FormatScheme 数据来初始化此新对象的数据。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果 FormatScheme 已经初始化（非 null），则抛出。 |


---

### isEmpty {#isEmpty}

| 名称 | 描述 |
| --- | --- |
| isEmpty () | True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且使用此主题对象的任何覆盖都已禁用。只读 boolean。 |

**返回：**
boolean


---