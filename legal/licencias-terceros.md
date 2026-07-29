# Licencias de terceros

**Cajas Etiquetadas** usa las bibliotecas de software libre que se listan abajo.
Todas se distribuyen bajo la **Licencia Apache, versión 2.0**, cuyo texto completo
está al final de esta página.

Esta atribución no es una cortesía: el apartado 4 de la propia Apache 2.0 obliga a
conservar los avisos de copyright y licencia al redistribuir el software, y una app
publicada redistribuye estas bibliotecas dentro de su paquete.

Última revisión: 29 de julio de 2026 · versión 1.0 de la aplicación.

---

## Google · AndroidX y Jetpack Compose

Copyright © The Android Open Source Project · Apache License 2.0

| Biblioteca | Versión | Para qué |
|---|---|---|
| `androidx.core:core-ktx` | 1.15.0 | Utilidades base de Android |
| `androidx.activity:activity-compose` | 1.9.3 | Integración de Compose con la Activity |
| `androidx.lifecycle:lifecycle-runtime-ktx` | 2.8.7 | Ciclo de vida |
| `androidx.lifecycle:lifecycle-runtime-compose` | 2.8.7 | Ciclo de vida en Compose |
| `androidx.lifecycle:lifecycle-viewmodel-compose` | 2.8.7 | ViewModel en Compose |
| `androidx.compose.ui:ui` | BOM 2024.12.01 | Interfaz declarativa |
| `androidx.compose.ui:ui-graphics` | BOM 2024.12.01 | Dibujo |
| `androidx.compose.ui:ui-tooling-preview` | BOM 2024.12.01 | Vistas previas |
| `androidx.compose.material3:material3` | BOM 2024.12.01 | Componentes Material 3 |
| `androidx.compose.material:material-icons-extended` | BOM 2024.12.01 | Iconos |
| `androidx.room:room-runtime` | 2.6.1 | Base de datos local |
| `androidx.room:room-ktx` | 2.6.1 | Room con corrutinas |
| `androidx.room:room-compiler` | 2.6.1 | Generación de código (solo compilación) |
| `androidx.camera:camera-core` | 1.4.1 | Cámara |
| `androidx.camera:camera-camera2` | 1.4.1 | Implementación Camera2 |
| `androidx.camera:camera-lifecycle` | 1.4.1 | Cámara atada al ciclo de vida |
| `androidx.camera:camera-view` | 1.4.1 | Vista previa de la cámara |

## JetBrains · Kotlin

Copyright © JetBrains s.r.o. y colaboradores de Kotlin · Apache License 2.0

Biblioteca estándar de Kotlin y corrutinas.

## ZXing

Copyright © ZXing Authors · Apache License 2.0

`com.google.zxing:core` 3.5.3 — genera los códigos QR de las etiquetas y los lee
desde la cámara. Página del proyecto: <https://github.com/zxing/zxing>

---

## Lo que la aplicación NO usa

Se hace constar expresamente porque afecta a tu privacidad:

- **Sin bibliotecas de analítica** de ningún tipo.
- **Sin bibliotecas de publicidad.**
- **Sin SDK de redes sociales** ni de inicio de sesión.
- **Sin servicios en la nube.** La aplicación no declara el permiso `INTERNET`.

---

## Texto de la Licencia Apache 2.0

```
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

Texto íntegro: <https://www.apache.org/licenses/LICENSE-2.0>
