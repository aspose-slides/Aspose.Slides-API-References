---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML テキストからスライドを作成し、コレクションの末尾に追加します。
type: docs
weight: 196
url: /ja/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI です。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## SlideCollection::AddFromHtml(System::String) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |

### 戻り値

追加されたスライド。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI です。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |

### 戻り値

追加されたスライド。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI です。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |

### 戻り値

追加されたスライド。

## 備考

```cpp
// Presentation クラスのインスタンスを作成します。
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // AddFromHtml メソッドを呼び出し、HTML ファイルを渡します。
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Save メソッドを使用して、ファイルを PowerPoint ドキュメントとして保存します。
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)