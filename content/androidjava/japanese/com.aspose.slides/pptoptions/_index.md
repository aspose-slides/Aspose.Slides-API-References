---
title: PptOptions
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: プレゼンテーションを PPT 形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/pptoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

プレゼンテーションを PPT 形式で保存する方法を制御するオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID（CLSID）を表します。 |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID（CLSID）を表します。 |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID（CLSID）を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID を 'Microsoft Powerpoint.Show.8' に設定
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


ルート ディレクトリ エントリに格納されているオブジェクト クラス GUID（CLSID）を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID を 'Microsoft Powerpoint.Show.8' に設定
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID |  |