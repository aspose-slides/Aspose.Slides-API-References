---
title: LoadExternalFonts
second_title: Aspose.Slides for .NET API 参考
description: 添加额外的文件夹以查找字体。
type: docs
weight: 40
url: /zh/aspose.slides/fontsloader/loadexternalfonts/
---

## FontsLoader.LoadExternalFonts 方法

添加额外的文件夹以查找字体。

```csharp
public static void LoadExternalFonts(string[] directories)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| directories | String[] | 用于读取额外字体的目录。 |

### 例子

以下示例演示如何从 .TTF 加载自定义字体

```csharp
[C#]
// 文档目录的路径。
string dataDir = "C:\\";
// 查找字体的文件夹
String[] folders = new String[] { dataDir };
// 加载自定义字体目录中的字体
FontsLoader.LoadExternalFonts(folders);
// 执行一些工作并进行演示/幻灯片渲染
using (Presentation presentation = new Presentation(dataDir + "DefaultFonts.pptx"))
{
    presentation.Save(dataDir + "NewFonts_out.pptx", SaveFormat.Pptx);
    // 清除字体缓存
    FontsLoader.ClearCache();
}
```

### 另请参见

* class [FontsLoader](../../fontsloader)
* namespace [Aspose.Slides](../../fontsloader)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: 由 xmldocmd 为 Aspose.Slides.dll 生成 -->