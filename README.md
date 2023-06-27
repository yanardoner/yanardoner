- 👋 Hi, I’m @yanardoner
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
yanardoner/yanardoner is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

print("Merhaba!")

meme_dict = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Komik bir şeye verilen cevap",
            "ROFL": "bir şakaya karşılık cevap",
            "SHEESH": "onaylamamak",
            "CREEPY": "korkunç",
            "AGGRO": "agresifleşmek/sinirlenmek",
            }

for i in range(5):
    word = input("Anlamadığınız bir kelime yazın (hepsini büyük harflerle yazın!): ")
    
    if word in meme_dict.keys():
        print(meme_dict[word])
    else:
        print("Sözlükte böyle bir kelime bulunmamakta!")
