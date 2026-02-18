# propuesta_NFL_Stadiums

La base de datos NFL Stadium Attendance contiene información sobre la asistencia a los estadios de la NFL a lo largo de múltiples temporadas. Está compuesto por 3 tablas principales: games, attendance y standings, las cuales se pueden relacionar con los atributos team, year y week. 

Los datos fueron recopilados a partir de fuentes públicas de estadísticas deportivas, principalmente de plataformas como Pro Football Reference y datos abiertos disponibles en Kaggle. Se espera una actualización anual aunque la última fue hace 2 años. 

Los datos fueron subidos a Kaggle por Sunjay Kapadnis y están disponibles en https://www.kaggle.com/datasets/sujaykapadnis/nfl-stadium-attendance-dataset. No se incluyó un propósito explícito para su recolección.

La entidad attendance contiene aproximadamente 10,849 tuplas y 8 atributos. El atributo 'team' es la abreviatura del equipo, 'team_name' es el nombre completo, 'year' es el año de la temporada, 'week' es el número de semana de la temporada, 'weekly_attendance' es la asistencia en esa semana, 'home' asistencia total en juegos de local, 'away' asistencia total en juegos de visitante y 'total' asistecnia total general. Los atributos numéricos: son 'year', 'week', 'weekly_attendance', 'home', 'away', 'total'. Los atributos 'team' y 'team_name' son categóricos, el atributo 'team_name' es de texto y los atributos 'year' y 'week' son temporales. 

La entidad games tiene aproximadamente 7,800 tuplas y 19 atributos. El atributo 'year' es el año de la temporada, 'week' es el número de semana de la temporada, 'home_team' es el equipo que juega de local, 'away_team' el equipo que visita, 'winner' es el ganador, 'tie' si hubo un empate, 'day' en que día de la semana jugaron, 'date' es la fecha del partido, 'time' es la hora del partido, 

La entidad Games contiene información detallada de cada partido. 

El objetivo de estos datos es realizar un análisis de cómo la asistencia al estadio y el rendimiento se afectan. ¿Una buena asistencia causa un buen rendimiento, o el buen rendimiento de un equipo produce mejor asistencia? ¿Cuáles son los equipos que más llenan su estadio? Este análisis puede ser aplicado en predicciones deportivas y análisis de datos interno de los equipos.

Las implicaciones éticas que conlleva este análisis incluyen pero no se limitan a su uso para hacer apuestas deportivas o los efectos que su uso en el análisis interno de los equipos puedan tener en el precio o disponibilidad de los boletos para los juegos.
