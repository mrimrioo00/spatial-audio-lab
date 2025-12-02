# spatial-audio-lab
A laboratory for experimenting with spatial audio and immersive sound generation using Python.

---

## 🎧 Overview
This project explores the fundamentals of:
- Spatial audio (立体音響)
- Immersive sound design
- Multi-source panning and positioning
- Basic DSP (Digital Signal Processing)
- Interactive audio behaviors

実験を積み重ねながら立体音響の仕組みを理解していきます。

---

## 🛠 Tech Stack
- Python 3.x  
- `numpy` — vector & math operations  
- `soundfile` / `pydub` — audio I/O  
- `scipy` — signal processing (予定)  
- `pygame` / `PyQt` — UI prototyping (予定)

---

## 📂 Project Structure（予定）

/src  
/audio        # 音声処理モジュール  
/spatial      # 空間音響アルゴリズム  
/utils        # 補助関数  
/tests          # 学習用テストコード  
/docs           # メモや資料  


---

## 🚀 Planned Features
- [ ] 単一音源の左右・前後・距離パン  
- [ ] 複数音源を三次元空間に配置  
- [ ] 距離減衰（distance attenuation）  
- [ ] 部屋の簡易反射 / リバーブのシミュレーション  
- [ ] GUI を使ったインタラクティブ再生  
- [ ] 小さなミニアプリ（例：音を探す“Sound Finder”）

---

## 🧪 How to Run

pip install -r requirements.txt  
python src/main.py  
※音声ファイルは後で追加予定。    
※実験的なコードが多く、書き換えが頻繁に発生します。  


---

## 📝 Notes
This is a learning project.  
Specifications and implementations may change often as the project evolves.

学習目的のため、コードは頻繁に更新・改善されます。  

---

## 📄 License
MIT License

---

## 👤 Author
Mirai Sanagi  
Exploring sound × Python × immersive audio design  
