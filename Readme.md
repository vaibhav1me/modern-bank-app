In React, you should never update the state using the previous version of that same old state, instead create a callback function with prev state as an argument. This way react makes sure that it keeps the state up to date