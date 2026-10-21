# Vehículo de carga Liviana Tipo Motocicleta

Recorrido web inmersivo del proyecto de grado 11D, Técnico en Mecánica Automotriz, I. E. Carlos Julio Torrado Peñaranda, Ábrego.

## Uso

Servir `dist/` con cualquier servidor estático. Por ejemplo, `python3 -m http.server 4175 --directory dist`. Avanzar con scroll, flechas de teclado o los controles inferiores. El modelo permanece visible y la cámara recorre sus componentes. El botón Giro libre permite explorar y Recentrar regresa al encuadre del capítulo. Pausar detiene los movimientos automáticos.

## Estructura y fuentes

Los 14 capítulos siguen la presentación entregada por el equipo: portada, integrantes, introducción, objetivos, bujía, bobina captora, carrocería y suspensión, transmisión, frenos, presupuesto, fabricación, montaje, apoyos y cierre. Los ocho nombres, fotografías y 16 conceptos de presupuesto proceden del archivo PRESENTACION DEL PROYECTO- TECNICO EN MECANICA AUTOMOTRIZ-GRADO 11D-ABREGO.pptx. El presupuesto suma COP 984.000.

La maqueta 3D es geometría propia aproximada basada en las fotografías del prototipo. Los cortes y movimientos se amplían para explicar los principios. No se atribuyen medidas, carga admisible o ensayos certificados al prototipo. El ejemplo de transmisión 12/36 dientes es ilustrativo. La captora se distingue del estator. Las tolerancias de mantenimiento dependen del manual del motor específico.

Las fuentes técnicas primarias y el alcance están disponibles en Fuentes y modelo. El guion PDF está en assets/Guion_Motocarro.pdf.

## Implementación

Sitio estático, módulos JavaScript, Three.js r169 (licencia MIT incluida en assets), GSAP y una composición HyperFrames de 12 segundos para la reducción por cadena. El adaptador web reproduce la composición automáticamente en su capítulo y respeta la pausa global. No requiere compilación ni servicios de pago.

Los escudos del colegio, SENA y TecnoParque se conservan como material institucional facilitado para esta presentación educativa. Las fotografías pertenecen al material del proyecto.
