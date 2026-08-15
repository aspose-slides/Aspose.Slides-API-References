---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API 參考
description: 將投影片內容另存為 EMF 檔案。
type: docs
weight: 170
url: /zh-hant/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 方法

將投影片內容儲存為 EMF 檔案。

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目標串流 |
## 備註

以下程式碼範例示範如何將 PowerPoint 簡報的第一張投影片轉換為中繼檔案。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// 將第一張投影片儲存為中繼檔案
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [Slide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)