---
title: MasterThemeManager
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/masterthememanager/
---
## MasterThemeManager 类

 提供对演示文稿主主题的访问。
 
### applyColorScheme {#applyColorScheme}

| Name | Description |
| --- | --- |
| applyColorScheme ([ExtraColorScheme](../extracolorscheme)) | 将额外的配色方案应用于幻灯片。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| scheme | [ExtraColorScheme](../extracolorscheme) | IExtraColorScheme 对象。 |

 **返回：**
void


---


### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | 返回主题对象。 |

 **返回：**
ThemeEffectiveData


---


### getOverrideTheme {#getOverrideTheme}

| Name | Description |
| --- | --- |
| getOverrideTheme () | 返回覆盖的主题对象。读/写 IMasterTheme。 |

 **返回：**
[MasterTheme](../mastertheme)


---


### isOverrideThemeEnabled {#isOverrideThemeEnabled}

| Name | Description |
| --- | --- |
| isOverrideThemeEnabled () | 确定 OverrideTheme 是否覆盖继承的有效主题（Presentation.MasterTheme），读/写 boolean。 |

 **返回：**
boolean


---


### setOverrideTheme {#setOverrideTheme}

| Name | Description |
| --- | --- |
| setOverrideTheme ([MasterTheme](../mastertheme)) | 返回覆盖的主题对象。读/写 IMasterTheme。 |

 **返回：**
void


---


### setOverrideThemeEnabled {#setOverrideThemeEnabled}

| Name | Description |
| --- | --- |
| setOverrideThemeEnabled (boolean) | 确定 OverrideTheme 是否覆盖继承的有效主题（Presentation.MasterTheme），读/写 boolean。 |

 **返回：**
void


---