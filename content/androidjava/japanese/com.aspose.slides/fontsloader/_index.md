---
title: FontsLoader
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ユーザーが定義したカスタムフォントをロードするためのクラスです。
type: docs
url: /ja/com.aspose.slides/fontsloader/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)  
```
public final class FontsLoader implements IFontsLoader
```

ユーザーが定義したカスタムフォントをロードするためのクラスです。プレゼンテーションオブジェクトを作成する前に使用する必要があります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 追加フォルダーを検索してフォントを取得します。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | バイナリデータからフォントを追加します |
| [getFontFolders()](#getFontFolders--) | フォントフォルダーを取得します。 |
| [clearCache()](#clearCache--) | ユーザーが定義したすべてのカスタムフォントを解放します |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

フォントを検索するための追加フォルダーを追加します。

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // フォントを検索するフォルダー
>  String[] folders = new String[] { dataDir };
>  // カスタムフォントディレクトリのフォントをロード
>  FontsLoader.loadExternalFonts(folders);
>  // いくつかの作業を行い、プレゼンテーション/スライドのレンダリングを実行
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // フォントキャッシュをクリア
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| directories | java.lang.String[] | 追加フォントを読み込むディレクトリ。 |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

バイナリデータからフォントを追加します

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| data | byte[] | フォントのデータ |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

フォントフォルダーを取得します。LoadExternalFonts メソッドで追加されたフォルダーとシステムのフォントフォルダーを返します。

**戻り値:**
java.lang.String[] - フォルダー名を含む配列

### clearCache() {#clearCache--}
```
public static void clearCache()
```

ユーザーが定義したすべてのカスタムフォントを解放します

--------------------

このメソッドはユーザーが定義したカスタムフォントのキャッシュをクリアする必要があります。