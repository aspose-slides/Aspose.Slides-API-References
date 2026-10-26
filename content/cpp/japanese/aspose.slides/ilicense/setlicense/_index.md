---
title: SetLicense()
second_title: Aspose.Slides for C++ APIリファレンス
description: コンポーネントにライセンスを設定します。
type: docs
weight: 1
url: /ja/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) メソッド

コンポーネントにライセンスを設定します。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 完全なファイル名または短いファイル名、または埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。 |
## 備考

次の場所でライセンスを検索します。

1. 明示的なパス。
2. コンポーネント アセンブリのフォルダー。
3. クライアントの呼び出しアセンブリのフォルダー。
4. エントリ アセンブリのフォルダー。
5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**Note:** .NET Compact Framework では、ライセンスを次の場所だけで検索します。

1. 明示的なパス。
2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内に MyLicense.lic という名前のライセンス ファイルを検索しようとします。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) メソッド

コンポーネントにライセンスを設定します。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ライセンスが含まれるストリーム。 |
## 備考

このメソッドを使用して、ストリームからライセンスを読み込みます。

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ILicense](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)