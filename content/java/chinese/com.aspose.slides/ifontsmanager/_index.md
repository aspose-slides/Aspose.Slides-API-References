---
title: IFontsManager
second_title: Aspose.Slides for Java API 参考
description: 管理演示文稿中的字体。
type: docs
url: /zh/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

管理演示文稿中的字体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 在渲染时使用的字体替换 读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 在渲染时使用的字体替换 读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 表示用户的 FontFallBack 规则集合，用于管理字体集合以通过回退功能进行正确的替换 读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 表示用户的 FontFallBack 规则集合，用于管理字体集合以通过回退功能进行正确的替换 读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回演示文稿中使用的字体 |
| [getSubstitutions()](#getSubstitutions--) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入在演示文稿中的字体 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 删除嵌入的字体 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 添加嵌入的字体。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 添加嵌入的字体 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 替换演示文稿中的字体 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 中提供的信息替换演示文稿中的字体 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合中提供的信息替换演示文稿中的字体 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 检索表示指定字体样式和字体数据的字节数组。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 确定给定字节数组和字体名称的字体嵌入级别。 |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 指定是否在具有相同字体名称和样式的情况下优先使用已注册的字体而非嵌入字体。 |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 指定是否在具有相同字体名称和样式的情况下优先使用已注册的字体而非嵌入字体。 |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

在渲染时使用的字体替换 读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**返回:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

在渲染时使用的字体替换 读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

表示用户的 FontFallBack 规则集合，用于管理字体集合以通过回退功能进行正确的替换 读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 从 FontsManager 获取空的或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或者
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 在 FontsManager 中用新集合替换现有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

表示用户的 FontFallBack 规则集合，用于管理字体集合以通过回退功能进行正确的替换 读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 从 FontsManager 获取空的或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或者
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 在 FontsManager 中用新集合替换现有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

返回演示文稿中使用的字体

**返回:**
com.aspose.slides.IFontData[] - 字体数组
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

获取将在演示文稿渲染时被替换的字体信息。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字体替换 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 的集合。
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

获取在指定幻灯片渲染期间将被替换的字体信息。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slides | int[] | 要检索字体替换信息的幻灯片索引数组，索引从 1 开始。 |

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 指定幻灯片的所有字体替换（[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)）集合。
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

返回嵌入在演示文稿中的字体

**返回:**
com.aspose.slides.IFontData[] - 嵌入的字体 IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

删除嵌入的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字体数据对象 [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

添加嵌入的字体。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字体数据对象 [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 嵌入字体规则 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

请注意，在复制任何字体时，大多数字体都有版权。请事先查找字体的许可证，并确认它们可以自由转移到另一台机器。 |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

添加嵌入的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | byte[] | 字体数据  byte[]  |
| embedFontRule | int | 嵌入字体规则 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

请注意，在添加任何字体时，大多数字体都有版权。请事先查找字体的许可证，并确认它们可以自由转移到另一台机器。 |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

替换演示文稿中的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 源字体 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目标字体 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 中提供的信息替换演示文稿中的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字体替换信息 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合中提供的信息替换演示文稿中的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字体替换信息集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

检索表示指定字体样式和字体数据的字节数组。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 检索演示文稿中使用的所有字体
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 获取表示演示文稿中第一个字体的常规样式的字节数组
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含关于字体 [IFontData](../../com.aspose.slides/ifontdata) 信息的字体数据对象。 |
| fontStyle | int | 要检索数据的字体样式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**返回:**
byte[] - 包含指定字体样式的字体数据的字节数组。如果未找到字体数据或样式，返回 null。
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

确定给定字节数组和字体名称的字体嵌入级别。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 检索演示文稿中使用的所有字体
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 获取表示演示文稿中第一个字体的常规样式的字节数组
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 确定字体的嵌入级别
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字体数据的字节数组。 |
| fontName | java.lang.String | 字体名称。 |

**返回:**
int - 指定字体的嵌入级别。
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

指定是否在具有相同字体名称和样式的情况下优先使用已注册的字体而非嵌入字体。启用后，匹配的嵌入字体将在导出期间暂时替换为相应的已注册字体。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

默认是  **false** 。

**返回:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

指定是否在具有相同字体名称和样式的情况下优先使用已注册的字体而非嵌入字体。启用后，匹配的嵌入字体将在导出期间暂时替换为相应的已注册字体。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

默认是  **false** 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |