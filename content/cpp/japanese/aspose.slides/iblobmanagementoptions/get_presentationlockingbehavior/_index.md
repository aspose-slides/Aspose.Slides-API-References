---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API リファレンス
description: "このプロパティは、Presentation クラスのインスタンスがインスタンス期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースをロックします。これは BLOB の操作時にメモリ使用量とパフォーマンスの向上に役立ちますが、ソース（ストリームまたはファイル）は Presentation のインスタンス期間中に変更できません。以下は例です："
type: docs
weight: 1
url: /ja/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() メソッド


このプロパティは、[Presentation](../../presentation/) クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースをロックします。これは BLOB の操作時にメモリ使用量とパフォーマンスの向上に役立ちますが、ソース（ストリームまたはファイル）は [Presentation](../../presentation/)'s インスタンスの存続期間中に変更できません。以下は例です：

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
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

* 列挙型 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* クラス [IBlobManagementOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)