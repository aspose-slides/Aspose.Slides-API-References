---
title: IPresentationInfo
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーション ファイルに関する情報
type: docs
url: /ja/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

プレゼンテーション ファイルに関する情報
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | バインドされたプレゼンテーションが暗号化されている場合は True、そうでない場合は False を取得します。 |
| [isPasswordProtected()](#isPasswordProtected--) | バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。 |
| [isWriteProtected()](#isWriteProtected--) | バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [getLoadFormat()](#getLoadFormat--) | バインドされたプレゼンテーションの形式を取得します。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 開くパスワードで保護されたプレゼンテーションに対して、パスワードが正しいかどうかをチェックします。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 書き込み保護されたプレゼンテーションに対して、変更用パスワードが正しいかどうかをチェックします。 |
| [readDocumentProperties()](#readDocumentProperties--) | バインドされたプレゼンテーションのドキュメント プロパティを取得します。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | バインドされたプレゼンテーションのプロパティを更新します。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | バインドされたプレゼンテーションをストリームへ書き込みます。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | バインドされたプレゼンテーションをファイルへ書き込みます。 |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

バインドされたプレゼンテーションが暗号化されている場合は True、そうでない場合は False を取得します。読み取り専用 boolean。

**戻り値:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**戻り値:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

プレゼンテーションが開くためのパスワードで保護されている場合、プロパティ値は NotDefined になります。[NullableBool](../../com.aspose.slides/nullablebool) 列挙体を参照してください。

**戻り値:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

バインドされたプレゼンテーションの形式を取得します。読み取り専用 [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

開くパスワードで保護されたプレゼンテーションに対して、パスワードが正しいかどうかをチェックします。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | 確認するパスワード。 |

--------------------

パスワードが null または空の場合、このメソッドは false を返します。 |

**戻り値:**
boolean - プレゼンテーションが開くパスワードで保護されており、パスワードが正しい場合は True、そうでない場合は false。
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

書き込み保護されたプレゼンテーションに対して、変更用パスワードが正しいかどうかをチェックします。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | 確認するパスワード。 |

--------------------

1. このメソッドを呼び出す前に (\#isWriteProtected.isWriteProtected) プロパティを確認してください。 2. パスワードが null または空の場合、このメソッドは false を返します。 |

**戻り値:**
boolean - プレゼンテーションが書き込み保護されており、パスワードが正しい場合は True。そうでない場合は false。
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

バインドされたプレゼンテーションのドキュメント プロパティを取得します。

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - ドキュメント プロパティ [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

バインドされたプレゼンテーションのプロパティを更新します。

--------------------

> ```
> このサンプルは、#updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) メソッドを呼び出す方法を示します。
>  #readDocumentProperties.readDocumentProperties メソッドの呼び出しで返されるドキュメント プロパティを更新します。
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | ドキュメント プロパティ [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

バインドされたプレゼンテーションをストリームへ書き込みます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ストリームはシーク可能かつ書き込み可能である必要があります。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

バインドされたプレゼンテーションをファイルへ書き込みます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | プレゼンテーション ファイル。 |