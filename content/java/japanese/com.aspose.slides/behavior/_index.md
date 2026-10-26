---
title: Behavior
second_title: Aspose.Slides for Java API リファレンス
description: エフェクトの基底クラスの動作を表します。
type: docs
url: /ja/com.aspose.slides/behavior/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

エフェクトの基底クラスの動作を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | アニメーション動作が蓄積されるかどうかを表します。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | アニメーション動作が蓄積されるかどうかを表します。 |
| [getAdditive()](#getAdditive--) | 現在のアニメーション動作が他の実行中のアニメーションと結合されているかどうかを表します。 |
| [setAdditive(int value)](#setAdditive-int-) | 現在のアニメーション動作が他の実行中のアニメーションと結合されているかどうかを表します。 |
| [getProperties()](#getProperties--) | 動作のプロパティを表します。 |
| [getTiming()](#getTiming--) | エフェクト動作のタイミングプロパティを表します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | エフェクト動作のタイミングプロパティを表します。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

アニメーション動作が蓄積されるかどうかを表します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

アニメーション動作が蓄積されるかどうかを表します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

現在のアニメーション動作が他の実行中のアニメーションと結合されているかどうかを表します。読み書き可能 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**戻り値:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

現在のアニメーション動作が他の実行中のアニメーションと結合されているかどうかを表します。読み書き可能 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

動作のプロパティを表します。読み取り専用 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**戻り値:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

エフェクト動作のタイミングプロパティを表します。読み書き可能 [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

エフェクト動作のタイミングプロパティを表します。読み書き可能 [ITiming](../../com.aspose.slides/itiming)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |