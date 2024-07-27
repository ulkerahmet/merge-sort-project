# Merge Sort Project

Merge Sort, diziyi küçük parçalara bölerek ve bu parçaları sıralayarak çalışır. İşte adım adım Merge Sort aşamaları:

1. **Diziyi ikiye böl:** 
    - Sol: [16, 21, 11]
    - Sağ: [8, 12, 22]

2. **Alt dizileri tekrar ikiye böl:**
    - Sol:
        - [16, 21]
        - [11]
    - Sağ:
        - [8, 12]
        - [22]

3. **Alt dizileri tekrar ikiye böl:**
    - Sol:
        - [16]
        - [21]
        - [11]
    - Sağ:
        - [8]
        - [12]
        - [22]

4. **Alt dizileri sıralı şekilde birleştir:**
    - Sol:
        - [16, 21]
        - [11]
    - Sağ:
        - [8, 12]
        - [22]

5. **Birleştir ve sıralamaya devam et:**
    - Sol:
        - [11, 16, 21]
    - Sağ:
        - [8, 12, 22]

6. **Son olarak iki ana diziyi birleştir ve sıralı hale getir:**
    - [8, 11, 12, 16, 21, 22]

Her bir aşamada dizinin nasıl ikiye bölündüğünü ve bu parçaların sıralanarak tekrar birleştirildiğini görüyoruz.

### Big-O Gösterimi:
Merge Sort'un zaman karmaşıklığı her zaman \( O(n \log n) \)'dir. Bu, en iyi, en kötü ve ortalama durumlar için geçerlidir.