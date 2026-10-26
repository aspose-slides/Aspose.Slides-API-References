---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 列挙型

**io.RawIOBase** がメソッドに渡される場合、バイナリラージオブジェクト (BLOB) とみなされます ([`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions) の説明を参照)。この列挙型の値は、**io.RawIOBase** がメソッドに渡されたときにどのように扱われるかを示します。要件に応じて、最も効率的な動作を提供するためのさまざまな判断が行われます。

LoadingStreamBehavior 型は次のメンバーを公開します:

## フィールド

| フィールド | 説明 |
| :- | :- |
| READ_STREAM_AND_RELEASE | ストリームは最後まで読み取られ、その後解放されます。つまり、このストリームが将来 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンスによって使用されないことが保証されます。クライアントコードで閉じることも、他の方法で使用することも可能です。 |
| KEEP_LOCKED | ストリームは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) オブジェクト内でロックされ、所有権が転送されます。[`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) オブジェクトは、このオブジェクトが破棄される際にストリームを正しく破棄する責任があります。この動作は、大きな BLOB ファイル (大容量のビデオやオーディオ – [`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions) の説明を参照) をシリアライズし、メモリへのロードやその他のパフォーマンス問題を防止したい場合に非常に有用です。単に **System.IO.FileStream** を開いてメソッドに渡し、[`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/ja/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior を選択すれば済みます。 |


### 参照
* クラス [`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)