## **📌 My Profile Site**
自己紹介ページ

### **🔹 概要**
このプロジェクトは、Python の Flask を使用した自己紹介ページです。  
仮想環境を用いて Flask の実行環境を構築し、ローカルで簡単に動作させることができます。

---

## **🔹 使用技術**
- **言語**: Python, HTML, CSS
- **フレームワーク**: Flask
- **環境**: 仮想環境 (`venv`)
- **ツール**: Git, GitHub

---

## **🔹 セットアップ手順**
### **1. リポジトリをクローン**
まず、GitHub からプロジェクトをローカルにクローンします。

```sh
git clone https://github.com/your-username/my-profile-site.git
cd my-profile-site
```

### **2. 仮想環境を作成**
仮想環境 `venv_profile` を作成し、Python の環境を分離します。

```sh
python -m venv venv_profile
```

### **3. 仮想環境を有効化**
OS に応じて以下のコマンドを実行してください。

#### **Windows (Git Bash)**
```sh
source venv_profile/Scripts/activate
```

#### **Mac/Linux**
```sh
source venv_profile/bin/activate
```

仮想環境が有効化されると、ターミナルに `(venv_profile)` が表示されます。

---

## **🔹 必要なライブラリをインストール**
仮想環境が有効になったら、必要なライブラリ（Flask）をインストールします。

```sh
pip install -r requirements.txt
```

---

## **🔹 アプリの実行**
Flask アプリを起動するには、以下のコマンドを実行します。

```sh
python app.py
```

**起動後、以下のURLにアクセスしてください。**  
[http://127.0.0.1:5000/](http://127.0.0.1:5000/)

**⚠️ もし `5000` ポートが使用中の場合は、別のポート（例：8080）で実行してください。**
```sh
python app.py --port 8080
```
その場合、[http://127.0.0.1:8080/](http://127.0.0.1:8080/) にアクセスしてください。

---

## **🔹 ディレクトリ構成**
```
my-profile-site/
│── venv_profile/             # 仮想環境（ライブラリのみ管理）
│── .gitignore                # Git無視ファイル（venv を除外）
│── README.md                 # プロジェクトの説明
│── requirements.txt          # 必要なライブラリのリスト
│── app.py                    # Flask アプリのメインスクリプト
│── static/                   # CSS, 画像など
│   ├── style.css
│   ├── profile.jpg           # プロフィール画像（任意）
│── templates/                # HTMLテンプレート
│   ├── index.html            # 自己紹介ページ
```

---

## **🔹 プロフィール**
- **名前**: 玉井大智
- **大学**: 九州大学 法学部
- **スキル**: Python / SQL / Excel
- **GitHub**: [your-github-link](https://github.com/your-github)
- **メール**: your-email@example.com

---

## **🔹 開発メモ**
✅ **仮想環境を終了する場合**
```sh
deactivate
```

✅ **Flask のバージョンを確認する場合**
```sh
python -m flask --version
```

✅ **他のポートで Flask を実行する場合**
```sh
python app.py --port 8080
```

---

## **🔹 ライセンス**
このプロジェクトは MIT ライセンスのもとで公開されています。

---

**💡 この `README.md` を GitHub に追加するには**
```sh
git add README.md
git commit -m "README を追加"
git push origin main
```
