[@substrate/txwrapper](../README.md) › [Globals](../globals.md) › ["src/methods/session/setKeys"](_src_methods_session_setkeys_.md)

# Module: "src/methods/session/setKeys"

## Index

### Interfaces

* [SessionSetKeysArgs](../interfaces/_src_methods_session_setkeys_.sessionsetkeysargs.md)

### Functions

* [setKeys](_src_methods_session_setkeys_.md#setkeys)

## Functions

###  setKeys

▸ **setKeys**(`args`: [SessionSetKeysArgs](../interfaces/_src_methods_session_setkeys_.sessionsetkeysargs.md), `info`: [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md), `options?`: Partial‹[Options](../interfaces/_src_util_options_.options.md)›): *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*

*Defined in [src/methods/session/setKeys.ts:25](https://github.com/paritytech/txwrapper/blob/9698841/src/methods/session/setKeys.ts#L25)*

Sets the session key(s) of the function caller to `key`.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`args` | [SessionSetKeysArgs](../interfaces/_src_methods_session_setkeys_.sessionsetkeysargs.md) | - |
`info` | [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md) | Information required to construct the transaction.  |
`options?` | Partial‹[Options](../interfaces/_src_util_options_.options.md)› | - |

**Returns:** *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*