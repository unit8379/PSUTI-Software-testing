# PSUTI-Software-testing
Лабороторные работы по курсу Тестирование ПО

Проект BaseCalculator содержит само приложение тестирумого калькулятора. На основе классов этого проекта составлялось юнит-тестирование.

Проект Lab_2_TestDriver содержит 2-ую и 3-ю лабораторные работы.
Это оконное приложение тестового драйвера, где автоматизировались тестовые примеры для выбранной операции калькулятора и тестовые примеры для методов класса AnalaizerClass. В третьей лабораторной работе тестировался AnalaizerClass.cs класс калькулятора, но он компилируется в рантайме. Файл этого класса содержится в самом проекте: Lab_2_TestDriver/AnalaizerClass.cs.

Проект Lab_4_UnitTest содержит 4-ую лабораторную работу.
В этой работе составлялись автоматизированные юнит-тесты для методов класса AnalaizerClass. Созданные юнит-тесты можно запустить в Обозревателе тестов в Visual Studio.

Проект Lab_5_PlayList_UnitTest содержит 5-ую лабораторную работу.
В этой работе составлялись автоматизированные юнит-тесты для методов работы с памятью калькулятора (класс BaseCalc.cs). Текстбокс с выражением не статичени и приватен, поэтому пришлось прямо в классе BaseCalcTests воссоздать работу тестируемых методов и вызывать именно их во время тестирования.

Проект Lab_6_Integration_Testing содержит 6-ую лабораторную работу.
В этой работе составлялись автоматизированные юнит-тесты для методов, которые совершают последовательный вызов всех модулей системы калькулятора, т. е. произовдят интеграцию. Тестировались метод Estimate() класса AnalaizerClass и метод Main() класса Program.
