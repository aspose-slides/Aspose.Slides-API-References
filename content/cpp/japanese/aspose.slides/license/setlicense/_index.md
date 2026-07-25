---
title: SetLicense()
second_title: Aspose.Slides for C++ API リファレンス
description: コンポーネントにライセンスを付与します。
type: docs
weight: 14
url: /ja/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) メソッド

コンポーネントにライセンスを付与します。

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 完全なファイル名または短いファイル名、または埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。 |

## 備考

次の場所でライセンスを探します:

1. 明示的なパス。
2. コンポーネント アセンブリのフォルダー。
3. クライアントの呼び出しアセンブリのフォルダー。
4. エントリ アセンブリのフォルダー。
5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**注:** .NET Compact Framework では、ライセンスは次の場所でのみ検索されます:

1. 明示的なパス。
2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソースの順に、MyLicense.lic という名前のライセンス ファイルを探します。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) メソッド

コンポーネントにライセンスを付与します。

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ライセンスを含むストリーム。 |

## 備考

このメソッドを使用して、ストリームからライセンスをロードします。

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [License](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)