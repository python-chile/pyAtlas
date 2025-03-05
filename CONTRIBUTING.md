# Contribución PyAtlas

---

Reglas que se deben seguir para poder aportar al proyecto, bajo las [normas](https://github.com/python-chile/docs/blob/master/normativa-trabajo-github.md)  de Python Chile. Favor seguir el paso a paso, cualquier aporte que no siga las bases es rechazado.

Se compone de tres tópicos, descritos a continuación, cada uno abarca un objetivo específico para crecer el proyecto de forma ordenada.

**Importante**: Todo aporte al proyecto y discusión se exige que sea de forma respetuosa hacia integrantes del proyecto.

---

## Contribución relacionado con una Issue
Para el caso que haya una issue creada y bajo esta se hace un aporte, basarse en lo siguiente:

### Issue
- La creación de una issue sólo está permitido para el caso en que se detecte algún bug, error, falla o corrección que se deba hacer en el proyecto, dicha corrección por ejemplo, puede ser eliminar o actualizar algún elemento de la lista. Esta issue debe contar con su respectiva descripción.
- Cualquier persona puede crear una issue, como también se puede asignar una issue para resolverla, creada por si mismo o por terceros.

### Pull Request
- Debe existir de forma previa su correspondiente issue.
- Se debe enlazar dicha issue en la pull request.
- Debe contener una breve descripción del aporte.
- Respetar revisión y tiempos de codeowners.
- Debe contener al menos una aprobación, cualquier cambio que se pida, se anula la(s) aprobacion(es) previa(s).
- Merge y squash para finalizar la pull request.

### Nomenclatura rama
- Debe seguir el formato pch-<tipo>-<número issue>-<breve titulo> ejemplo pch-fix-34-enlaces-libs-data
- Tener en consideración:
  - Tipo: Puede ser fix o feature.
  - Breve título: Una descripción relacionado con la issue.

## Contribución sin una issue relacionada
Para el caso de aportes simples que sólo agregar elementos a la lista, basarse en lo siguiente:

### Pull request
- Debe contener sólo nuevos elementos que se agregan a la lista, se debe respetar todos los campos, nombre, enlace, descripción y tipo. 
- Se puede agregar tantos elementos como se quiera, no es necesario que pertenezcan a un mismo tipo estos elementos, es decir, se puede agregar librerías, frameworks u otros al mismo tiempo.
- Opcionalmente puede contener una descripción.
- Se debe respetar revisión y tiempos de codeowners.
- Debe contener al menos una aprobación, cualquier cambio nuevo, anula la mínima aprobación previa.

### Nomenclatura rama
- Debe seguir el formato pch-<tipo>-<breve titulo> ejemplo pch-feature-framworks-web
- Tener en consideración:
  - Tipo: Debe ser feature
  - Breve título: Descripción breve, no es necesario que sea descriptivo en su totalidad ya que dentro de esta puede haber un mix de libs, tools, u otros que no tengan une relación para ser abarcados en el título.

## Discussion
Necesario para el caso de nuevas ideas que se quieran agregar al proyecto, puede ser, flujo de trabajo, mejorar formato de la lista, actualizar la tabla simbología del proyecto, proposición de una mejora del proyecto en general, 
en resumen, cualquier tema que no pertenezca a una issue o agregar elementos a la lista.
La creación de un _discussion_ debe contener su correspondiente tag.