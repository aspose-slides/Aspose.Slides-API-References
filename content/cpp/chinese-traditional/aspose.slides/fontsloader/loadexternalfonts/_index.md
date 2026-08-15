---
title: LoadExternalFonts()
second_title: Aspose.Slides for C++ API 參考
description: 新增額外的資料夾以搜尋字型。
type: docs
weight: 1
url: /zh-hant/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) 方法

新增額外的資料夾以搜尋字型。

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 要讀取額外字型的目錄。 |
## 備註

以下範例說明如何從 .TTF 載入自訂字型
```cpp
// 文件目錄的路徑。
System::String dataDir = u"C:\\";

// 用於搜尋字型的資料夾
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// 載入自訂字型目錄的字型
FontsLoader::LoadExternalFonts(folders);

// 執行一些工作並進行簡報/投影片的渲染
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// 清除字型快取
FontsLoader::ClearCache();
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [FontsLoader](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)