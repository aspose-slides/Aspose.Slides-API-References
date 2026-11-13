---
title: FontsManager
second_title: Aspose.Slides for Java API 参考
description: 在演示文稿中管理字体。
type: docs
url: /zh/com.aspose.slides/fontsmanager/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)  
```
public class FontsManager implements IFontsManager
```

在整个演示文稿中管理字体。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 加载演示文稿
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 加载要替换的源字体
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // 保存演示文稿
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 用于渲染的字体替换。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 用于渲染的字体替换。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行正确的替换。读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行正确的替换。读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回演示文稿中使用的字体 |
| [getSubstitutions()](#getSubstitutions--) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 获取在指定幻灯片渲染期间将被替换的字体信息。 |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 指定是否应优先使用已注册字体而不是具有相同字体名称和样式的嵌入字体。 |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 指定是否应优先使用已注册字体而不是具有相同字体名称和样式的嵌入字体。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入在演示文稿中的字体。 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 移除嵌入的字体。 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 添加嵌入的字体。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 添加嵌入的字体。 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 在演示文稿中替换字体。 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 提供的信息在演示文稿中替换字体。 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 集合提供的信息在演示文稿中替换字体。 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 检索表示指定字体样式和字体数据的字节数组。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 确定从给定字节数组和字体名称得到的字体嵌入级别。 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

用于渲染的字体替换。读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**返回:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

用于渲染的字体替换。读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行正确的替换。读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 获取来自 FontsManager 的空或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 用新集合替换 FontsManager 中的现有集合
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行正确的替换。读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 获取来自 FontsManager 的空或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 并在 FontsManager 中用新集合替换现有集合 
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
public final IFontData[] getFonts()
```

返回演示文稿中使用的字体

**返回:**
com.aspose.slides.IFontData[] - 字体数组

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字体替换的集合 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| slides | int[] | 用于检索字体替换信息的幻灯片索引数组，起始索引为 1。 |

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 指定幻灯片的所有字体替换的集合 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

指定是否应在具有相同字体名称和样式的嵌入字体上优先使用已注册字体。启用后，匹配的嵌入字体将在导出期间临时替换为相应的已注册字体。

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

默认是 **false**。

**返回:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

指定是否应在具有相同字体名称和样式的嵌入字体上优先使用已注册字体。启用后，匹配的嵌入字体将在导出期间临时替换为相应的已注册字体。

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

默认是 **false**。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

返回嵌入在演示文稿中的字体

**返回:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

移除嵌入的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

添加嵌入的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

添加嵌入的字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

在演示文稿中替换字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 源字体 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目标字体 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 提供的信息在演示文稿中替换字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字体替换信息 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 集合提供的信息在演示文稿中替换字体

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字体替换规则集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

检索表示指定字体样式和字体数据的字节数组。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 检索演示文稿中使用的所有字体
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 获取演示文稿中第一个字体的常规样式对应的字节数组
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含字体 [IFontData](../../com.aspose.slides/ifontdata) 信息的字体数据对象。 |
| fontStyle | int | 要检索数据的字体样式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**返回:**
byte[] - 包含指定字体样式的字体数据的字节数组。如果未找到字体数据或样式，则返回 null。

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

确定给定字节数组和字体名称对应的字体嵌入级别。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 检索演示文稿中使用的所有字体
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 获取演示文稿中第一个字体的常规样式对应的字节数组
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
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
| fontName | java.lang.String | 字体的名称。 |

**返回:**
int - 指定字体的嵌入级别。