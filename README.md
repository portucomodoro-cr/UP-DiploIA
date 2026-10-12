# UP-DiploIA
Trabajo Practico Nro 1
Alumno: Héctor Alejandro Ramos
Curso: Diplomatura en Inteligencia Artificial
Universidad de Palermo


Trabajo Práctico Nº 1

Consigna 1:
	
El dataset seleccionado, contiene datos de pólizas de seguros.

A continuación, ser presenta el diccionario de variables: 

Variable				                  Descripción
policy_id				                  Identificador único del asegurado
policy_tenure				              Antigüedad de la póliza
age_of_car				                Antigüedad del vehículo (normalizada)
age_of_policyholder			          Edad del titular de la póliza (normalizada)
area_cluster  				            Zona geográfica donde reside el asegurado
population_density			          Densidad de población en la zona donde reside el asegurado
make					                    Código del fabricante (codificado)
segment					                  Segmento del vehículo (A / B1 / B2 / C1 / C2)
model					                    Modelo de vehículo (codificado)
fuel_type				                  Tipo de combustible
max_torque				                Torque máximo
max_power				                  Potencia máxima
engine_type				                Tipo de motor utilizado en el vehículo
airbags 				                  Cantidad de airbags con que cuenta el vehículo
is_esc					                  Vehículo equipado con ESC (Control de Estabilidad)
is_adjustable_steering    		    Vehículo con volante regulable 
is_tpms 				                  Vehículo equipado con TPMS (Presión de neumáticos)
is_parking_sensors			          Vehículo con sensores de estacionamiento 
is_parking_camera			            Vehículo con cámara de retroceso 
rear_brakes_type			            Tipo de frenos traseros (Tambor o Disco)
displacement				              Cilindrada del motor
cylinder				                  Cantidad de cilindros del motor
transmission_type 			          Tipo de transmisión
gear_box				                  Cantidad de marchas
steering_type				              Tipo de dirección
turning_radius				            Radio de giro de la dirección (en metros)
length					                  Largo del vehículo
width					                    Ancho del vehículo
height 					                  Altura del vehículo
gross_weight				              Peso máximo admitido por el vehiculo (pasajeros, carga y equipamiento)
is_front_fog_lights			          Cuenta con faros antiniebla delanteros
is_rear_window_wiper			        Posee limpiaparabrisas en la luneta trasera
is_rear_window_washer			        Posee lavaluneta (zorrino o zapito trasero)
is_rear_window_defogger			      Cuenta con desempañador de luneta
is_brake_assist				            Tiene asistencia al frenado (ABS)
is_power_door_locks			          Posee bloqueo eléctrico de puertas
is_central_locking			          Posee cierre centralizado de puertas
is_power_steering			            Cuenta con direcciòn asistida
is_driver_seat_height_adjustable	Cuenta con butaca regulable en altura para el conductor
is_day_night_rear_view_mirror		  Espejo retrovisor con funcion "Día/Noche"
is_ecw 					                  Cuenta con testigo de falla de motor (Check Engine)
is_speed_alert 				            Cuenta con sistema de alerta de velocidad
ncap_rating				                Calificación de serguridad asignada por el NCAP
is_claim				                  Denuncia de Siniestro (0="No reclamo" - 1="Denuncia")


Consigna 2:
	
	Hipótesis:

1.	Los vehículos más antiguos, considerados de colección, ¿presentan una 	menor tasa de reclamos? (Los propietarios de estos vehículos suelen utilizarlos solo para encuentros o exposiciones).
2.	¿La tasa de siniestros, está relacionada con la edad del asegurado?
3.	¿En las zonas más pobladas (con mayor densidad poblacional), el índice de reclamos es mayor?
4.	¿La antigüedad del asegurado en la compañía, influye sobre la probabilidad de reclamo?
5.	¿Los vehículos más grandes, generan mayor cantidad de reclamos?
6.	¿Los autos con motores de mayor potencia, provocan más siniestros?
7.	¿Los vehículos equipados con sistemas de seguridad, presentan menos tasa de reclamos?


	Hallazgos: 
1.	Los titulares de pólizas mayores a 50 años son propensos a generar mayor porcentaje de reclamos, considerar lanzar campañas para captar clientes por debajo de esta edad.
2.	Las características mecánicas y de seguridad de los vehículos analizados en este conjunto de datos, no resultaron relevantes para tomar decisiones a cerca de promociones futuras.
