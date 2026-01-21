# eaharec.com - Temario HAREC

Sitio web de código abierto con el temario completo para la preparación del examen de obtención del diploma de operador de estaciones de radioaficionado en España.

**Web:** [eaharec.com](https://eaharec.com)

## Contenido

El temario sigue el programa oficial establecido en el **Anexo II de la Orden IET/1311/2013** (Reglamento de uso del dominio público radioeléctrico por radioaficionados), conforme a la **Recomendación CEPT T/R 61-02**.

### Parte I: Electricidad y Radioelectricidad

1. Teoría de la electricidad, electromagnetismo y radio
2. Componentes
3. Circuitos
4. Receptores
5. Transmisores
6. Antenas y líneas de transmisión
7. Propagación
8. Medidas
9. Interferencia e inmunidad
10. Seguridad

### Parte II: Normativa Reglamentaria

1. Alfabeto fonético internacional
2. Código Q
3. Abreviaturas
4. Señales de socorro, urgencia y seguridad
5. Distintivos de llamada
6. Planes de bandas IARU
7. Responsabilidad social del radioaficionado
8. Reglamentación nacional e internacional
9. Inspección y régimen sancionador

## Información del examen

- **Duración:** 90 minutos
- **Formato:** Test por ordenador en JPIT provincial
- **Aprobado:** 50% en cada parte independiente
- **Resultado:** Certificado HAREC (conforme a CEPT T/R 61-02)

## Uso local

```bash
# Clonar el repositorio
git clone https://github.com/t00mas/eaharec.git

# Abrir en navegador (no requiere servidor)
open index.html

# O usar un servidor local
python3 -m http.server 8000
# Abrir http://localhost:8000
```

## Estructura del proyecto

```
radio/
├── index.html              # Página principal
├── recursos.html           # Enlaces y recursos
├── css/
│   └── style.css          # Estilos
├── parte1/
│   ├── index.html         # Índice Parte I
│   ├── tema1.html         # Teoría electricidad
│   ├── tema2.html         # Componentes
│   └── ...
├── parte2/
│   ├── index.html         # Índice Parte II
│   ├── tema1.html         # Alfabeto fonético
│   ├── tema2.html         # Código Q
│   └── ...
└── README.md
```

## Contribuir

Las contribuciones son bienvenidas:

1. Fork del repositorio
2. Crear rama (`git checkout -b mejora/tema-x`)
3. Commit (`git commit -m 'Añade contenido tema X'`)
4. Push (`git push origin mejora/tema-x`)
5. Abrir Pull Request

### Guía de estilo

- HTML semántico
- CSS con variables en `:root`
- Sin dependencias externas (excepto Google Fonts)
- Contenido basado exclusivamente en fuentes oficiales

## Referencias legales

- [Orden IET/1311/2013](https://www.boe.es/buscar/act.php?id=BOE-A-2013-7624) - Reglamento de radioaficionados
- [SETID - Exámenes](https://avance.digital.gob.es/espectro/radioaficionados/Paginas/examenes-radioaficionado.aspx) - Información oficial
- [Resolución 3/6/2014](https://www.boe.es/buscar/act.php?id=BOE-A-2014-6322) - Procedimiento del examen

## Licencia

Contenido educativo basado en normativa pública. El código del sitio se distribuye bajo licencia MIT.

---

**Disclaimer:** Este sitio no está afiliado al Gobierno de España ni a ningún organismo oficial. Es un proyecto educativo independiente.

