# vscode-devcontainer-java-sample

## 概要

VSCodeの拡張機能 `Dev Containers` を利用して、dockerコンテナ上でJavaプログラムを動作させるサンプルプロジェクト。

## サンプルプログラムの実行方法

```bash
# ビルド
mvn package

# プログラムを実行
mvn exec:java -Dexec.mainClass="com.qwerty0121.vscode.devcontainer.java.sample.App"
```
