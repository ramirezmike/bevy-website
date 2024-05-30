`WorldCell` has been removed. If you were using it to fetch multiple distinct values from a `&mut World`, use `SystemState` by calling `SystemState::get` instead. Alternatively, if `SystemState` cannot be used, `UnsafeWorldCell` can instead be used in unsafe contexts.