---
title: IPptOptions
second_title: Android 用 Aspose.Slides の Java API リファレンス
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
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | オブジェクトクラス GUID (CLSID) を表します。これはルート ディレクトリ エントリに格納されます。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。 |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | オブジェクトクラス GUID (CLSID) を表します。これはルート ディレクトリ エントリに格納されます。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。 |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


オブジェクトクラス GUID (CLSID) を表します。これはルート ディレクトリ エントリに格納されます。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。

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


オブジェクトクラス GUID (CLSID) を表します。これはルート ディレクトリ エントリに格納されます。ドキュメントのアプリケーションの COM アクティベーションに使用できます。デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応しています。

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