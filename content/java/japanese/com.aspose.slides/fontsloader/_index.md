---
title: FontsLoader
second_title: Aspose.Slides for Java API リファレンス
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

ユーザーが定義したカスタムフォントをロードするクラスです。プレゼンテーションオブジェクトを作成する前に使用する必要があります。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | フォントを検索するための追加フォルダーを追加します。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | バイナリ データからフォントを追加します。 |
| [getFontFolders()](#getFontFolders--) | フォントフォルダーを取得します。 |
| [clearCache()](#clearCache--) | ユーザーが定義したすべてのカスタムフォントを解放します。 |
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
>  // カスタムフォントディレクトリのフォントをロードする
>  FontsLoader.loadExternalFonts(folders);
>  // いくつかの処理を実行し、プレゼンテーション/スライドのレンダリングを行う
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // フォントキャッシュをクリアする
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| directories | java.lang.String[] | 追加フォントを読み取るディレクトリ。 |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


バイナリ データからフォントを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | フォントのデータ |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


フォントフォルダーを取得します。LoadExternalFonts メソッドで追加されたフォルダーとシステムフォントフォルダーの両方を返します。

**戻り値:**
java.lang.String[] - フォルダー名を含む配列
### clearCache() {#clearCache--}
```
public static void clearCache()
```


ユーザーが定義したすべてのカスタムフォントを解放します。

--------------------

このメソッドはユーザーが定義したカスタムフォントのキャッシュをクリアする必要があります。