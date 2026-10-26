---
title: IPresentationFactory
second_title: Aspose.Slides for Java API リファレンス
description: COM インターフェイスを使用してプレゼンテーションを作成できます
type: docs
url: /ja/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

COM インターフェイスを使用してプレゼンテーションを作成できます
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createPresentation()](#createPresentation--) | 新しいプレゼンテーションを作成します。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 追加のロードオプションを使用して新しいプレゼンテーションを作成します |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | 指定されたファイルのプレゼンテーション情報を取得します。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | 指定されたストリームのプレゼンテーション情報を取得します。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 配列から既存のプレゼンテーションを読み取ります |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 追加のロードオプションを使用して配列から既存のプレゼンテーションを読み取ります |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | ストリームから既存のプレゼンテーションを読み取ります |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 追加のロードオプションを使用してストリームから既存のプレゼンテーションを読み取ります |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | ファイルから既存のプレゼンテーションを読み取ります |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 追加のロードオプションを使用してストリームから既存のプレゼンテーションを読み取ります |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | スライドから生テキストを取得します |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | スライドから生テキストを取得します |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | スライドから生テキストを取得します |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

新しいプレゼンテーションを作成します。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新しいプレゼンテーション
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

追加のロードオプションを使用して新しいプレゼンテーションを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新しいプレゼンテーション
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

指定されたファイルのプレゼンテーション情報を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | プレゼンテーションファイル。 |

**戻り値:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - プレゼンテーション情報
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

指定されたストリームのプレゼンテーション情報を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | プレゼンテーションストリーム。 |

**戻り値:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - プレゼンテーション情報。
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

配列から既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | 読み取る配列 |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

追加のロードオプションを使用して配列から既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | 読み取る配列 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

ストリームから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み取る入力ストリーム |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

追加のロードオプションを使用してストリームから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み取る入力ストリーム |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPPresentation readPresentation(String file)
```

ファイルから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | ファイル名 |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

追加のロードオプションを使用してストリームから既存のプレゼンテーションを読み取ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | ファイル名 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation) - 読み取ったプレゼンテーション
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | 入力ファイル |
| mode | int | 抽出モード |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列を含む PresentationText のインスタンス
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム |
| mode | int | 抽出モード |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列を含む PresentationText のインスタンス
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

スライドから生テキストを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム |
| mode | int | 抽出モード |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ロードオプション |

**戻り値:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - スライドテキスト配列を含む PresentationText のインスタンス