---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 列挙体

[`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) ソース（ファイルまたは **io.RawIOBase**）を [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) のインスタンスの読み込みおよび操作中に扱う際の動作を表します。

PresentationLockingBehavior タイプは以下のメンバーを公開します。

## フィールド

| フィールド | 説明 |
| :- | :- |
| LOAD_AND_RELEASE | ソースは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) コンストラクタの実行中のみロックされます。<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) が false に設定されている場合、すべての BLOB がメモリにロードされます。そうでない場合、一時ファイルなど他の手段が使用される可能性があります。この動作は [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ja/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) よりも遅く、ソースの所有権を [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) に渡すことが可能な場合は [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ja/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) を使用することが推奨されます。 |
| KEEP_LOCKED | ソースは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンスの存続期間全体にわたってロックされ、破棄されるまで保持されます。<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) を true に設定する必要があります。この動作を使用するには、そうしないと例外がスローされます。この動作は推奨されており、[`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/ja/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE) よりも高速でメモリ消費が少なくなります。 |

### 備考

ソースは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) コンストラクタに渡されるパラメータです。以下の例では、ソースは "pres.pptx" ファイルです。

この例では、ソース（"pres.pptx" ファイル）は [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンスの存続期間中ロックされ、他のプロセスによって変更または削除できません。

### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)