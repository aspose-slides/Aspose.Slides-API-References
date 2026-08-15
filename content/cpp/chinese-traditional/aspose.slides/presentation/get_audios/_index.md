---
title: get_Audios()
second_title: Aspose.Slides for C++ API 參考
description: 返回簡報中所有嵌入音訊檔案的集合。只讀 IAudioCollection.
type: docs
weight: 222
url: /zh-hant/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() 方法

返回演示文稿中所有嵌入音訊檔案的集合。只讀 [IAudioCollection](../../iaudiocollection/)。

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## 備註

以下範例示範如何將超連結新增至音訊檔案。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioCollection](../../iaudiocollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)