---
title: BaseOverrideThemeManager
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/baseoverridethememanager/
---
## BaseOverrideThemeManager 类

 基类，用于提供对不同类型重写主题的访问。

### applyColorScheme {#applyColorScheme}

| 名称 | 描述 |
| --- | --- |
| applyColorScheme ([ExtraColorScheme](../extracolorscheme)) | 将额外的配色方案应用于幻灯片。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| scheme | [ExtraColorScheme](../extracolorscheme) | IExtraColorScheme 对象。 |

 **返回：**
void


---


### createThemeEffective {#createThemeEffective}

| 名称 | 描述 |
| --- | --- |
| createThemeEffective () | 返回主题对象。 |

 **返回：**
ThemeEffectiveData


---


### getOverrideTheme {#getOverrideTheme}

| 名称 | 描述 |
| --- | --- |
| getOverrideTheme () | 返回覆盖主题对象。 读写 IOverrideTheme。 |

 **返回：**
[OverrideTheme](../overridetheme)


---


### isOverrideThemeEnabled {#isOverrideThemeEnabled}

| 名称 | 描述 |
| --- | --- |
| isOverrideThemeEnabled () | 确定 OverrideTheme 是否覆盖继承的有效主题。 要启用 OverrideTheme 进行覆盖，请使用 OverrideTheme.Init*() 方法。 要禁用 OverrideTheme 的覆盖，请使用 OverrideTheme.Clear() 方法。 只读 boolean。 |

 **返回：**
boolean


---


### setOverrideTheme {#setOverrideTheme}

| 名称 | 描述 |
| --- | --- |
| setOverrideTheme ([OverrideTheme](../overridetheme)) | 返回覆盖主题对象。 读写 IOverrideTheme。 |

 **返回：**
void


---