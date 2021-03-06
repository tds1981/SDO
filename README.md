# SDO
Distance education and testing system
Представляется инструментальный программно-технический комплекс  для осуществления локального  дистанционного образования и автоматизированных тестирований (на ПК или спец. терминалах) в отдельно взятом учебном заведении на протяжении всего учебного процесса. Система представляет собой пакет клиентских программ, серверную базу данных и специальную терминальную подсистему для тестового контроля знаний .
Дружественный интерфейс клиентских программ обеспечивает следующие  функциональные возможности :
Создание и накопление электронных учебных пособий (в формате HTML) ;
Дистанционная индивидуальная образовательная работа преподавателя с обучаемым  (назначение теоретического материала и тестовых опросов по нему);
Создание и накопление тестовых заданий  различных типов;
Создание и накопление тестовых опросов различных типов;
Проведение автоматизированных тестирований обучаемых по разным дисциплинам на ПЭВМ и на специальных терминалах, в соответствии с календарным планом;
Учёт успеваемости и накопление различной статистической информации, необходимой для построения эффективного учебного процесса;
Учёт преподавательского состава и обучаемых в рамках существующих в ВУЗе структурных подразделений;
Создание и распечатка различных отчётов;
В системе определено 4 типа пользователей: «АДМИНИСТРАТОР», «ПРЕПОДАВАТЕЛЬ», «ТЬЮТОР», «СТУДЕНТ», каждому типу пользователя соответствует свое клиентское приложение: 
1. Администратор, при необходимости, редактирует структуру ВУЗа, добавляет новые дисциплины и проводит изменение пользовательского состава системы (добавление и удаление преподавателей, студентов, тьюторов). 
2. Преподаватель осуществляет построение дисциплин (создание иерархической структуры дисциплины), формирует электронный учебник и тестовые задания, группируя их в соответствии со структурой дисциплины, а из тестовых заданий варианты опросов различных типов. Далее преподаватель может создавать календарный образовательный план, назначая студентам тестовые опросы и разделы учебного пособия.  
3. Тьютор - это пользователь, инициирующий и контролирующий процесс тестирования как на терминалах, так и на ПЭВМ. Тьютор контролирует работу сервера учебных пособий. 
4. Cтудент обладает регулируемым доступом к библиотеке (серверу) электронных учебных пособий и проходит тестирования в соответствии с образовательным планом. 
Использование недорогих терминалов для тестового контроля знаний, созданных на базе микроконтроллера PICmicro, решает вопрос невозможности проведения одновременного тестирования большого количества обучаемых в ВУЗе где нет для этого необходимого количества ПЭВМ. Терминалы объединены в сеть подключённую к серверу и обслуживаются программой «ТЬЮТОР», работающей в фоновом режиме.
Информация хранимая в базе данных имеет два уровня защиты, которые вместе с механизмом парольной защиты клиентских программ, обеспечивают ограничение доступа к ней лицам не имеющим соответствующих прав.
