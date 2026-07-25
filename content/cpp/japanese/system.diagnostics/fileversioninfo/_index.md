---
title: FileVersionInfo
second_title: Aspose.Slides for C++ API リファレンス
description: "ファイル バージョンに関する情報を提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 1
url: /ja/system.diagnostics/fileversioninfo/
---
## FileVersionInfo クラス

ファイル バージョンに関する情報を提供します。 このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。

```cpp
class FileVersionInfo
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | 製品バージョン フィールドを取得します。 |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | ファイル バージョン情報を取得します；未実装です。 |

## 参照

* 名前空間 [System::Diagnostics](../)
* ライブラリ [Aspose.Slides](../../)