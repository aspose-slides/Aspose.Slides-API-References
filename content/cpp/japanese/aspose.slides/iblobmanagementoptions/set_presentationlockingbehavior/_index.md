---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API リファレンス
description: "このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースをロックします。これにより BLOB を使用する際のメモリ消費とパフォーマンスが向上しますが、Presentation のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できません。以下は例です："
type: docs
weight: 14
url: /ja/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) メソッド


このプロパティは、[Presentation](../../presentation/) クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になるかどうかを定義します。インスタンスが所有者である場合、ソースをロックします。これにより BLOB の使用時のメモリ消費とパフォーマンスが向上しますが、[Presentation](../../presentation/) のインスタンス存続期間中はソース（ストリームまたはファイル）を変更できなくなります。以下は例です：

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## 備考



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Presentation の存続期間中に pres.pptx がロックされているため、IOException がスローされます
    // File::Delete(u"pres.pptx");
}
// Presentation オブジェクトが破棄された後、ファイルのロックが解除され、削除できるようになります
IO::File::Delete(u"pres.pptx");
```

## 参照

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)