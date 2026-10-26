---
title: get_Audios()
second_title: Aspose.Slides for C++ API 参考
description: 返回演示文稿中所有嵌入音频文件的集合。只读 IAudioCollection。
type: docs
weight: 222
url: /zh/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() 方法


返回演示文稿中所有嵌入音频文件的集合。只读 [IAudioCollection](../../iaudiocollection/)。

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## 备注


以下示例展示了如何向音频文件添加超链接。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioCollection](../../iaudiocollection/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)