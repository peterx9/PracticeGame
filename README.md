# Ulearn | Практика "Игра"
# Продуктовая документация
## Основное
- Платформа: ПК
- Технологии: C#, MonoGame
- Язык: Русский
- Жанры: 2D, Top-Down, BulletHell, Fantasy, Roguelike
- Настроение: Мрачное
- Сеттинг: Средневековье (Medival)
- Длительность игры: до 5 минут
- Главная игровая механика: Необратимая смерть (PermaDeath)

## Сюжет
Главный герой - Рыцарь, которому необходимо сбежать из какой-либо локации, попутно расправляясь с врагами.

## Игровой мир
В игре присутствует 10 различных локаций, каждая из которых имеент своих уникальных противников.
#### Ниже представлены пары \<Локация> \<Противники>
- Заброшенный замок. Рыцари-зомби
- Темный лес. Гоблины
- Руины храма. Живые статуи
- Заброшенная деревня. Бандиты и Волки
- Горная пещера. Гигантские Пауки и Крылатые Химеры
- Подземные катакомбы. Скелеты и Нежить
- Мрачный сад. Гноллы
- Река с бурлящими порогами. Крокодилы и Водные элементали
- Запущенный замок. Рыцари-призраки и Полтергейсты
- Облака гроз. Грозовые Демоны и Летучие мыши

## Геймплей
Локация выбирается случайно.
Главный герой появляется в комнате, со случайным метательным предметом, с помощью которого будет сражаться первое время.
Со всех сторон будут появляться враги, которые будут идти в сторону Рыцаря. С некоторым шансом из поверженных врагов можно получить ресурсы и новое оружие. *Доступные виды оружия представлены ниже.*
Подобранное оружие имеет случайные характеристики.
После убийства некоторого количесва врагов будет открываться проход в следующую комнату.

Комнаты бывают нескольких видов:
- Обычные
  - Необходимо убить N количество врагов
- Специальные
  - Магазин в котором можно приобрести снаряжение за ресурсы собранные с врагов
  - Кузница в которой иожно перековать оружие для того чтобы повысить его характеристики
  - Святилище в котором можно восполнить здоровье. *Даже если здоровье полное, Рыцарь получит бонус, игнорируя максимальный запас здоровья*
- Арена
  - Комната, в которой нужно сражаться с боссом

Всего необходимо преодолеть 10 комнат:
1-3 комнаты - Обычные
4-ая комната - Специальная
5-ая комната - Арена. Мини-босс
6-8 комнаты - Обычные
9-ая комната - Специальная
10-ая комната - Арена. Финальный Босс

Виды оружия:
- Ручница
- Мушкет
- Аркебуза
- Кулеврина
- Карабин
- Ружьё
- Гарпун
- Пистолет
- Винтовка







