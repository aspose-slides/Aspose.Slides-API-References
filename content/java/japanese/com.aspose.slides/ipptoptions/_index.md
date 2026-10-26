---
title: IPptOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションが PPT 形式で保存される方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/ipptoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

プレゼンテーションが PPT 形式で保存される方法を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | ルート ディレクトリ エントリに保存されるオブジェクト クラス GUID (CLSID) を表します。 |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | ルート ディレクトリ エントリに保存されるオブジェクト クラス GUID (CLSID) を表します。 |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

ルート ディレクトリ エントリに保存されるオブジェクト クラス GUID (CLSID) を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は「64818D11-4F9B-11CF-86EA-00AA00B929E8」で、これは「Microsoft Powerpoint.Slide.8」に対応します。

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
public abstract void setRootDirectoryClsid(UUID value)
```

ルート ディレクトリ エントリに保存されるオブジェクト クラス GUID (CLSID) を表します。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は「64818D11-4F9B-11CF-86EA-00AA00B929E8」で、これは「Microsoft Powerpoint.Slide.8」に対応します。

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