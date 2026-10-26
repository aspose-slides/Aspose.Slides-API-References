---
title: LoadingStreamBehavior
second_title: Aspose.Slides for C++ API リファレンス
description: "メソッドに渡される System::IO::Stream はバイナリ大オブジェクト（BLOB）と見なされます（IBlobManagementOptions の説明を参照）。この列挙体の値は、System::IO::Stream がメソッドに渡されたときにどのように扱われるかを示します。要件に応じて、最も効率的な動作を提供するためにさまざまな決定が行われます。"
type: docs
weight: 6735
url: /ja/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 列挙体

メソッドに渡される[System::IO::Stream](../../system.io/stream/)はBinary Large Object（BLOB）として扱われます（[IBlobManagementOptions](../iblobmanagementoptions/)の説明を参照）。この列挙体の値は、[System::IO::Stream](../../system.io/stream/)がメソッドに渡されたときにどのように扱われるかを示します。要件に応じて、最も効率的な動作を提供するためにさまざまな決定が行われます。

```cpp
enum class LoadingStreamBehavior
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | ストリームは最後まで読み取られ、その後解放されます。つまり、将来的に[IPresentation](../ipresentation/)インスタンスがこのストリームを使用しないことが保証されます。クライアントコードで閉じることも、他の方法で使用することも可能です。 |
| KeepLocked | 1 | ストリームは[IPresentation](../ipresentation/)オブジェクト内でロックされ、ストリームの所有権が転送されます。[IPresentation](../ipresentation/)オブジェクトは、このオブジェクト自体が破棄される際にストリームを正しく破棄する責任を負います。この動作は、大きなBLOBファイル（大容量のビデオやオーディオなど - [IBlobManagementOptions](../iblobmanagementoptions/)の説明を参照）をシリアライズする必要があり、メモリへのロードやその他のパフォーマンス問題を防ぎたい場合に非常に有用です。このファイル用に[System::IO::FileStream](../../system.io/filestream/)を開き、[LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior を選択してメソッドに渡すだけで済みます。 |

## 参照

* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)