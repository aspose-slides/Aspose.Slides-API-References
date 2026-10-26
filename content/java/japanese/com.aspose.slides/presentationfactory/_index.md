---
title: PresentationFactory
second_title: Aspose.Slides for Java API リファレンス
description: COM インターフェイスを使用してプレゼンテーションを作成できます
type: docs
url: /ja/com.aspose.slides/presentationfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

COM インターフェイスを使用してプレゼンテーションを作成できます

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | プレゼンテーションファクトリの静的インスタンスです。 |
| [createPresentation()](#createPresentation--) | 新しいプレゼンテーションを作成します。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 追加のロードオプションで新しいプレゼンテーションを作成します |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | ファイルから新しい PresentationInfo オブジェクトを作成し、プレゼンテーションにバインドします。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | ストリームから新しい PresentationInfo オブジェクトを作成し、プレゼンテーションにバインドします。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 配列から既存のプレゼンテーションを読み取ります |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 追加のロードオプションで配列から既存のプレゼンテーションを読み取ります |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | ストリームから既存のプレゼンテーションを読み取ります |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 追加のロードオプションでストリームから既存のプレゼンテーションを読み取ります |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | ファイルから既存のプレゼンテーションを読み取ります |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 追加のロードオプションでストリームから既存のプレゼンテーションを読み取ります |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | スライドから生テキストを取得します |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | スライドから生テキストを取得します |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | スライドから生テキストを取得します |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

プレゼンテーションファクトリの静的インスタンスです。読み取り専用 [PresentationFactory](../../com.aspose.slides/presentationfactory)。

**戻り値:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

新しいプレゼンテーションを作成します。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新しいプレゼンテーション
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

追加のロードオプションで新しいプレゼンテーションを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新しいプレゼンテーション
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

ファイルから新しい PresentationInfo オブジェクトを作成し、プレゼンテーションにバインドします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | プレゼンテーション ファイル |

**戻り値:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - プレゼンテーションにバインドされた PresentationInfo
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

ストリームから新しい PresentationInfo オブジェクトを作成し、プレゼンテーションにバインドします。指定されたストリーム内のプレゼンテーション情報を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | プレゼンテーションのストリーム |

**戻り値:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - プレゼンテーションにバインドされた PresentationInfo
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

配列から既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | 読み取り用の配列 |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

追加のロードオプションで配列から既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | 読み取り用の配列 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

ストリームから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み取り用入力ストリーム |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

追加のロードオプションでストリームから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み取り用入力ストリーム |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

ファイルから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | ファイル名 |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPPresentation readPresentation(String file, ILoadOptions options)
```

追加のロードオプションでファイルから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | ファイル名 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取られたプレゼンテーション
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | 入力ファイル |
| mode | int | 抽出モード |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列（生テキスト）を含む PresentationText のインスタンス
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム |
| mode | int | 抽出モード |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列（生テキスト）を含む PresentationText のインスタンス
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム |
| mode | int | 抽出モード |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列（生テキスト）を含む PresentationText のインスタンス