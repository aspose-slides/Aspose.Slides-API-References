---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ APIリファレンス
description: "IPresentation ソース（ファイルまたは System::IO::Stream）を読み込み、IPPresentation のインスタンスで作業する際の動作を表します。"
type: docs
weight: 6748
url: /ja/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 列挙型

[IPresentation](../ipresentation/) ソース（ファイルまたは [System::IO::Stream](../../system.io/stream/)）を読み込み、[IPresentation](../ipresentation/) のインスタンスで作業する際の動作を表します。

```cpp
enum class PresentationLockingBehavior
```

### 列挙値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| LoadAndRelease | 0 | ソースは [IPresentation](../ipresentation/) コンストラクタの実行中のみロックされます。 |
| KeepLocked | 1 | ソースは [IPresentation](../ipresentation/) インスタンスの存続期間全体にわたってロックされ、破棄されるまで保持されます。 |

## 備考

[IPresentation](../ipresentation/) コンストラクタに渡されるパラメータがソースです。以下の例では、ソースは "pres.pptx" ファイルです。

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

この例では、ソース（"pres.pptx" ファイル）は [IPresentation](../ipresentation/) インスタンスの存続期間中ロックされます。つまり、他のプロセスから変更または削除できません。

## 参照

* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)