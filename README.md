# goit-algo-hw-06

Task2:
DFS (глибина-перший пошук): DFS намагається досліджувати якомога глибше, обираючи кожного разу перший доступний сусідній вузол. Цей алгоритм йде вглиб графа, що може призвести до довших або навіть не оптимальних шляхів. Оскільки DFS не гарантує, що знайде найкоротший шлях, його результати можуть включати обхід, який не є оптимальним.

BFS (ширина-перший пошук): BFS досліджує всі сусідні вузли на кожному рівні, перш ніж переходити до наступного рівня. Це забезпечує знаходження найкоротшого шляху між початковим та кінцевим вузлами у графі без ваг. BFS гарантує, що знайдений шлях буде найкоротшим в плані кількості ребер.

Шлях DFS довший за шлях BFS, це обумовлено тим, що DFS спочатку йде вглиб графа, можливо, в неправильному напрямку, тоді як BFS розглядає всі можливі варіанти на кожному рівні, гарантуючи найкоротший шлях.