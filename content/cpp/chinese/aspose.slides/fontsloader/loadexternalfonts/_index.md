---
title: LoadExternalFonts()
second_title: Aspose.Slides for C++ API 参考
description: 添加额外的文件夹以搜索字体。
type: docs
weight: 1
url: /zh/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) 方法

添加额外的文件夹以搜索字体。

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 用于读取额外字体的目录。 |

## 备注

以下示例展示了如何从 .TTF 加载自定义字体。

```cpp
// 文档目录的路径。
System::String dataDir = u"C:\\";

// 用于搜索字体的文件夹
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// 加载自定义字体目录中的字体
FontsLoader::LoadExternalFonts(folders);

// 执行一些操作并进行演示文稿/幻灯片渲染
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// 清除字体缓存
FontsLoader::ClearCache();
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [FontsLoader](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)