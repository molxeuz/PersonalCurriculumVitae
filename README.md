# Mateo Molina González - Digital CV

Bienvenido a mi currículum vitae digital. Este proyecto es una representación interactiva de mi trayectoria académica y profesional como estudiante de Ingeniería en Sistemas y Computación. 

![GitHub repo size](https://img.shields.io/github/repo-size/molxeuz/https://github.com/molxeuz/PersonalCurriculumVitae)
![GitHub contributors](https://img.shields.io/github/contributors/molxeuz/https://github.com/molxeuz/PersonalCurriculumVitae)
![GitHub stars](https://img.shields.io/github/stars/molxeuz/https://github.com/molxeuz/PersonalCurriculumVitae)
![GitHub forks](https://img.shields.io/github/forks/molxeuz/https://github.com/molxeuz/PersonalCurriculumVitae)

## 📊 Estadísticas

| **Estadística**               | **Valor**            |
|-------------------------------|----------------------|
| **Experiencia Laboral**       | 1 año                |
| **Proyectos Realizados**      | +27 proyectos        |
| **Habilidades**               | 10 habilidades       |
| **Idiomas**                   | 2 (Español, Inglés)  |

### 📈 Gráfica de Habilidades


### Explicaciones de cada sección:

1. **Estadísticas**: Muestra información relevante sobre tu experiencia, proyectos y habilidades.
2. **Gráfica de Habilidades**: Este es un espacio reservado donde puedes insertar un gráfico interactivo utilizando bibliotecas como Chart.js o Google Charts. 
3. **Características, Tecnologías, Cómo Usar, y Contribuciones**: Secciones estándar que explican el propósito y uso del proyecto.

### Visualización de Gráficas

Para incluir gráficos interactivos, puedes usar una biblioteca como **Chart.js**. A continuación, te muestro un ejemplo simple de cómo agregar un gráfico de barras:

```html
<canvas id="myChart" width="400" height="200"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['HTML', 'CSS', 'JavaScript', 'Python', 'C#'],
        datasets: [{
            label: 'Habilidades',
            data: [90, 85, 80, 75, 70],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>
