# Experimento_meds_parte I

El proyecto consta de 3 aplicaciones: (i) **primero**/primero_t, (ii) segundo y (iii) tercero.

Para la primera parte, existen 2 aplicaciones: primero (control) y primero_t (tratamiento).

La configuración (en settings) variará ligeramente por eso. Este aplicativo (primero) refiere al de control, por tanto la config es la siguiente:

- SESSION_CONFIG_DEFAULTS = dict(real_world_currency_per_point=1, participation_fee=5)
- SESSION_CONFIGS = [dict(name='Experimento', num_demo_participants=1, app_sequence=['no_mobile', 'primero', 'segundo', 'tercero'])]

Esta aplicación contiene lo siguiente:
1. Instrucciones
2. Template de contacto y botón de instrucciones
3. Preguntas de entendimiento de instrucciones con opciones aleatorias
