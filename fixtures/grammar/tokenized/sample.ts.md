# sample.ts

**1:** ```#!/usr/bin/env node```

| text | scope |
| -- | -- |
| ``` #! ``` | source.ts comment.line.shebang.ts punctuation.definition.comment.ts |
| ``` /usr/bin/env node ``` | source.ts comment.line.shebang.ts |

**2:** *blank line*

**3:** ```/**```

| text | scope |
| -- | -- |
| ``` /** ``` | source.ts comment.block.documentation.ts punctuation.definition.comment.ts |

**4:** ``` * sample.ts```

| text | scope |
| -- | -- |
| ```  * sample.ts ``` | source.ts comment.block.documentation.ts |

**5:** ``` * This is a sample `typescript` file for use with the grammar parser.```

| text | scope |
| -- | -- |
| ```  * This is a sample `typescript` file for use with the grammar parser. ``` | source.ts comment.block.documentation.ts |

**6:** ``` *```

| text | scope |
| -- | -- |
| ```  * ``` | source.ts comment.block.documentation.ts |

**7:** ``` * It will contain a mix of stuff.```

| text | scope |
| -- | -- |
| ```  * It will contain a mix of stuff. ``` | source.ts comment.block.documentation.ts |

**8:** ``` */```

| text | scope |
| -- | -- |
| ```   ``` | source.ts comment.block.documentation.ts |
| ``` */ ``` | source.ts comment.block.documentation.ts punctuation.definition.comment.ts |

**9:** *blank line*

**10:** *blank line*

**11:** ```// alias for uniqueFilterFnGenerator```

| text | scope |
| -- | -- |
| ``` // ``` | source.ts comment.line.double-slash.ts punctuation.definition.comment.ts |
| ```  alias for uniqueFilterFnGenerator ``` | source.ts |

**12:** ```export const uniqueFn = uniqueFilterFnGenerator;```

| text | scope |
| -- | -- |
| ``` export ``` | source.ts meta.var.expr.ts keyword.control.export.ts |
| ```   ``` | source.ts meta.var.expr.ts |
| ``` const ``` | source.ts meta.var.expr.ts storage.type.ts |
| ```   ``` | source.ts meta.var.expr.ts |
| ``` uniqueFn ``` | source.ts meta.var.expr.ts meta.var-single-variable.expr.ts meta.definition.variable.ts variable.other.readwrite.ts |
| ```   ``` | source.ts meta.var.expr.ts meta.var-single-variable.expr.ts |
| ``` = ``` | source.ts meta.var.expr.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.var.expr.ts |
| ``` uniqueFilterFnGenerator ``` | source.ts meta.var.expr.ts variable.other.readwrite.ts |
| ``` ; ``` | source.ts punctuation.terminator.statement.ts |

**13:** *blank line*

**14:** ```export function uniqueFilterFnGenerator<T>(): (v: T) => boolean;```

| text | scope |
| -- | -- |
| ``` export ``` | source.ts meta.function.ts keyword.control.export.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` function ``` | source.ts meta.function.ts storage.type.function.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` uniqueFilterFnGenerator ``` | source.ts meta.function.ts meta.definition.function.ts entity.name.function.ts |
| ``` < ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.begin.ts |
| ``` T ``` | source.ts meta.function.ts meta.type.parameters.ts entity.name.type.ts |
| ``` > ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.end.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` => ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts |
| ``` boolean ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts support.type.primitive.ts |
| ``` ; ``` | source.ts punctuation.terminator.statement.ts |

**15:** ```export function uniqueFilterFnGenerator<T, U>(extractFn: (v: T) => U): (v: T) => boolean;```

| text | scope |
| -- | -- |
| ``` export ``` | source.ts meta.function.ts keyword.control.export.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` function ``` | source.ts meta.function.ts storage.type.function.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` uniqueFilterFnGenerator ``` | source.ts meta.function.ts meta.definition.function.ts entity.name.function.ts |
| ``` < ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.begin.ts |
| ``` T ``` | source.ts meta.function.ts meta.type.parameters.ts entity.name.type.ts |
| ``` , ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.type.parameters.ts |
| ``` U ``` | source.ts meta.function.ts meta.type.parameters.ts entity.name.type.ts |
| ``` > ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.end.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` extractFn ``` | source.ts meta.function.ts meta.parameters.ts entity.name.function.ts |
| ``` : ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` => ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts |
| ``` U ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` => ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts |
| ``` boolean ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts support.type.primitive.ts |
| ``` ; ``` | source.ts punctuation.terminator.statement.ts |

**16:** ```export function uniqueFilterFnGenerator<T>(extractFn?: (v: T) => T): (v: T) => boolean {```

| text | scope |
| -- | -- |
| ``` export ``` | source.ts meta.function.ts keyword.control.export.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` function ``` | source.ts meta.function.ts storage.type.function.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` uniqueFilterFnGenerator ``` | source.ts meta.function.ts meta.definition.function.ts entity.name.function.ts |
| ``` < ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.begin.ts |
| ``` T ``` | source.ts meta.function.ts meta.type.parameters.ts entity.name.type.ts |
| ``` > ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.end.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` extractFn ``` | source.ts meta.function.ts meta.parameters.ts entity.name.function.ts |
| ``` ? ``` | source.ts meta.function.ts meta.parameters.ts keyword.operator.optional.ts |
| ``` : ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` => ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts |
| ``` T ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.function.return.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` => ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts |
| ``` boolean ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts support.type.primitive.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts |
| ``` { ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts punctuation.definition.block.ts |

**17:** ```    const values = new Set<T>();```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts |
| ``` const ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts entity.name.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts |
| ``` values ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts variable.object.property.ts meta.definition.property.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` = ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` new ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts keyword.operator.new.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts |
| ``` Set ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts entity.name.type.ts |
| ``` < ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts meta.type.parameters.ts punctuation.definition.typeparameters.begin.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts meta.type.parameters.ts entity.name.type.ts |
| ``` > ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts meta.type.parameters.ts punctuation.definition.typeparameters.end.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts meta.brace.round.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts new.expr.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts punctuation.terminator.statement.ts |

**18:** ```    const extractor = extractFn || (a => a);```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts |
| ``` const ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts entity.name.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts |
| ``` extractor ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts variable.object.property.ts meta.definition.property.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` = ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` extractFn ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts variable.other.readwrite.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` || ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts keyword.operator.logical.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.brace.round.ts |
| ``` a ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.arrow.ts variable.parameter.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.arrow.ts |
| ``` => ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.arrow.ts storage.type.function.arrow.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.arrow.ts |
| ``` a ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.arrow.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.field.declaration.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts punctuation.terminator.statement.ts |

**19:** ```    return (v: T) => {```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts |
| ``` return ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts entity.name.function.ts meta.definition.method.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` v ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```  =>  ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts |
| ``` { ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.definition.block.ts |

**20:** ```        const vv = extractor(v);```

| text | scope |
| -- | -- |
| ```          ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` const ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts storage.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts |
| ``` vv ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts meta.definition.variable.ts variable.other.readwrite.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts |
| ``` = ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts |
| ``` extractor ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.function-call.ts entity.name.function.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.brace.round.ts |
| ``` v ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.terminator.statement.ts |

**21:** ```        const ret = !values.has(vv);```

| text | scope |
| -- | -- |
| ```          ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` const ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts storage.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts |
| ``` ret ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts meta.definition.variable.ts variable.other.readwrite.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts |
| ``` = ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts |
| ``` ! ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts keyword.operator.logical.ts |
| ``` values ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.function-call.ts variable.other.object.ts |
| ``` . ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.function-call.ts punctuation.accessor.ts |
| ``` has ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.function-call.ts support.function.dom.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.brace.round.ts |
| ``` vv ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.var.expr.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.terminator.statement.ts |

**22:** ```        values.add(vv);```

| text | scope |
| -- | -- |
| ```          ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` values ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.function-call.ts variable.other.object.ts |
| ``` . ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.function-call.ts punctuation.accessor.ts |
| ``` add ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.function-call.ts support.function.dom.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.brace.round.ts |
| ``` vv ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.terminator.statement.ts |

**23:** ```        return ret;```

| text | scope |
| -- | -- |
| ```          ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` return ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts keyword.control.flow.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` ret ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts variable.other.readwrite.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.terminator.statement.ts |

**24:** ```    };```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts |
| ``` } ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts meta.method.declaration.ts meta.block.ts punctuation.definition.block.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts punctuation.terminator.statement.ts |

**25:** ```}```

| text | scope |
| -- | -- |
| ``` } ``` | source.ts meta.function.ts meta.return.type.ts meta.type.function.return.ts meta.object.type.ts punctuation.definition.block.ts |

**26:** *blank line*

**27:** ```export function unique<T>(src: T[]): T[] {```

| text | scope |
| -- | -- |
| ``` export ``` | source.ts meta.function.ts keyword.control.export.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` function ``` | source.ts meta.function.ts storage.type.function.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` unique ``` | source.ts meta.function.ts meta.definition.function.ts entity.name.function.ts |
| ``` < ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.begin.ts |
| ``` T ``` | source.ts meta.function.ts meta.type.parameters.ts entity.name.type.ts |
| ``` > ``` | source.ts meta.function.ts meta.type.parameters.ts punctuation.definition.typeparameters.end.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` src ``` | source.ts meta.function.ts meta.parameters.ts variable.parameter.ts |
| ``` : ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts |
| ``` T ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts entity.name.type.ts |
| ``` [ ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.tuple.ts meta.brace.square.ts |
| ``` ] ``` | source.ts meta.function.ts meta.parameters.ts meta.type.annotation.ts meta.type.tuple.ts meta.brace.square.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ``` : ``` | source.ts meta.function.ts meta.return.type.ts keyword.operator.type.annotation.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` T ``` | source.ts meta.function.ts meta.return.type.ts entity.name.type.ts |
| ``` [ ``` | source.ts meta.function.ts meta.return.type.ts meta.type.tuple.ts meta.brace.square.ts |
| ``` ] ``` | source.ts meta.function.ts meta.return.type.ts meta.type.tuple.ts meta.brace.square.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts |
| ``` { ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts punctuation.definition.block.ts |

**28:** ```    return [...(new Set(src))];```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts |
| ``` return ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts entity.name.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts |
| ``` [ ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.brace.square.ts |
| ``` ... ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts meta.brace.round.ts |
| ``` new ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts entity.name.type.ts |
| ```   ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts |
| ``` Set ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts entity.name.type.ts |
| ``` ( ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts meta.type.paren.cover.ts meta.brace.round.ts |
| ``` src ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts meta.type.paren.cover.ts entity.name.type.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts meta.type.paren.cover.ts meta.brace.round.ts |
| ``` ) ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.type.paren.cover.ts meta.brace.round.ts |
| ``` ] ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts meta.type.tuple.ts meta.brace.square.ts |
| ``` ; ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts punctuation.terminator.statement.ts |

**29:** ```}```

| text | scope |
| -- | -- |
| ``` } ``` | source.ts meta.function.ts meta.return.type.ts meta.object.type.ts punctuation.definition.block.ts |

**30:** *blank line*

**31:** ```function main() {```

| text | scope |
| -- | -- |
| ``` function ``` | source.ts meta.function.ts storage.type.function.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` main ``` | source.ts meta.function.ts meta.definition.function.ts entity.name.function.ts |
| ``` ( ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.begin.ts |
| ``` ) ``` | source.ts meta.function.ts meta.parameters.ts punctuation.definition.parameters.end.ts |
| ```   ``` | source.ts meta.function.ts |
| ``` { ``` | source.ts meta.function.ts meta.block.ts punctuation.definition.block.ts |

**32:** ```    console.log('Hello World.');```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.block.ts |
| ``` console ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.class.console.ts |
| ``` . ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts punctuation.accessor.ts |
| ``` log ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.function.console.ts |
| ``` ( ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` ' ``` | source.ts meta.function.ts meta.block.ts string.quoted.single.ts punctuation.definition.string.begin.ts |
| ``` Hello World. ``` | source.ts meta.function.ts meta.block.ts string.quoted.single.ts |
| ``` ' ``` | source.ts meta.function.ts meta.block.ts string.quoted.single.ts punctuation.definition.string.end.ts |
| ``` ) ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.block.ts punctuation.terminator.statement.ts |

**33:** *blank line*

**34:** ```    const values = [1, 2, 3, 3, 4, 2, 5, 6];```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.block.ts |
| ``` const ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts storage.type.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts |
| ``` values ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts meta.definition.variable.ts variable.other.readwrite.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.var-single-variable.expr.ts |
| ``` = ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts keyword.operator.assignment.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts |
| ``` [ ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts meta.brace.square.ts |
| ``` 1 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 2 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 3 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 3 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 4 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 2 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 5 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` , ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts punctuation.separator.comma.ts |
| ```   ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts |
| ``` 6 ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts constant.numeric.decimal.ts |
| ``` ] ``` | source.ts meta.function.ts meta.block.ts meta.var.expr.ts meta.array.literal.ts meta.brace.square.ts |
| ``` ; ``` | source.ts meta.function.ts meta.block.ts punctuation.terminator.statement.ts |

**35:** ```    console.log(values);```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.block.ts |
| ``` console ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.class.console.ts |
| ``` . ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts punctuation.accessor.ts |
| ``` log ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.function.console.ts |
| ``` ( ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` values ``` | source.ts meta.function.ts meta.block.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.block.ts punctuation.terminator.statement.ts |

**36:** ```    console.log(unique(values));```

| text | scope |
| -- | -- |
| ```      ``` | source.ts meta.function.ts meta.block.ts |
| ``` console ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.class.console.ts |
| ``` . ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts punctuation.accessor.ts |
| ``` log ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts support.function.console.ts |
| ``` ( ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` unique ``` | source.ts meta.function.ts meta.block.ts meta.function-call.ts entity.name.function.ts |
| ``` ( ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` values ``` | source.ts meta.function.ts meta.block.ts variable.other.readwrite.ts |
| ``` ) ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` ) ``` | source.ts meta.function.ts meta.block.ts meta.brace.round.ts |
| ``` ; ``` | source.ts meta.function.ts meta.block.ts punctuation.terminator.statement.ts |

**37:** ```}```

| text | scope |
| -- | -- |
| ``` } ``` | source.ts meta.function.ts meta.block.ts punctuation.definition.block.ts |

**38:** *blank line*

**39:** ```main();```

| text | scope |
| -- | -- |
| ``` main ``` | source.ts meta.function-call.ts entity.name.function.ts |
| ``` ( ``` | source.ts meta.brace.round.ts |
| ``` ) ``` | source.ts meta.brace.round.ts |
| ``` ; ``` | source.ts punctuation.terminator.statement.ts |

**40:** *blank line*
