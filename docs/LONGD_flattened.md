# Solidity API

## IERC20

_Interface of the ERC-20 standard as defined in the ERC._

### Contract
IERC20 : contracts/LONGD_flattened.sol

Interface of the ERC-20 standard as defined in the ERC.

 --- 
### Functions:
### totalSupply

```solidity
function totalSupply() external view returns (uint256)
```

_Returns the value of tokens in existence._

### balanceOf

```solidity
function balanceOf(address account) external view returns (uint256)
```

_Returns the value of tokens owned by `account`._

### transfer

```solidity
function transfer(address to, uint256 value) external returns (bool)
```

_Moves a `value` amount of tokens from the caller's account to `to`.

Returns a boolean value indicating whether the operation succeeded.

Emits a {Transfer} event._

### allowance

```solidity
function allowance(address owner, address spender) external view returns (uint256)
```

_Returns the remaining number of tokens that `spender` will be
allowed to spend on behalf of `owner` through {transferFrom}. This is
zero by default.

This value changes when {approve} or {transferFrom} are called._

### approve

```solidity
function approve(address spender, uint256 value) external returns (bool)
```

_Sets a `value` amount of tokens as the allowance of `spender` over the
caller's tokens.

Returns a boolean value indicating whether the operation succeeded.

IMPORTANT: Beware that changing an allowance with this method brings the risk
that someone may use both the old and the new allowance by unfortunate
transaction ordering. One possible solution to mitigate this race
condition is to first reduce the spender's allowance to 0 and set the
desired value afterwards:
https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729

Emits an {Approval} event._

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 value) external returns (bool)
```

_Moves a `value` amount of tokens from `from` to `to` using the
allowance mechanism. `value` is then deducted from the caller's
allowance.

Returns a boolean value indicating whether the operation succeeded.

Emits a {Transfer} event._

 --- 
### Events:
### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

_Emitted when `value` tokens are moved from one account (`from`) to
another (`to`).

Note that `value` may be zero._

### Approval

```solidity
event Approval(address owner, address spender, uint256 value)
```

_Emitted when the allowance of a `spender` for an `owner` is set by
a call to {approve}. `value` is the new allowance._

## IERC20Metadata

_Interface for the optional metadata functions from the ERC-20 standard._

### Contract
IERC20Metadata : contracts/LONGD_flattened.sol

Interface for the optional metadata functions from the ERC-20 standard.

 --- 
### Functions:
### name

```solidity
function name() external view returns (string)
```

_Returns the name of the token._

### symbol

```solidity
function symbol() external view returns (string)
```

_Returns the symbol of the token._

### decimals

```solidity
function decimals() external view returns (uint8)
```

_Returns the decimals places of the token._

inherits IERC20:
### totalSupply

```solidity
function totalSupply() external view returns (uint256)
```

_Returns the value of tokens in existence._

### balanceOf

```solidity
function balanceOf(address account) external view returns (uint256)
```

_Returns the value of tokens owned by `account`._

### transfer

```solidity
function transfer(address to, uint256 value) external returns (bool)
```

_Moves a `value` amount of tokens from the caller's account to `to`.

Returns a boolean value indicating whether the operation succeeded.

Emits a {Transfer} event._

### allowance

```solidity
function allowance(address owner, address spender) external view returns (uint256)
```

_Returns the remaining number of tokens that `spender` will be
allowed to spend on behalf of `owner` through {transferFrom}. This is
zero by default.

This value changes when {approve} or {transferFrom} are called._

### approve

```solidity
function approve(address spender, uint256 value) external returns (bool)
```

_Sets a `value` amount of tokens as the allowance of `spender` over the
caller's tokens.

Returns a boolean value indicating whether the operation succeeded.

IMPORTANT: Beware that changing an allowance with this method brings the risk
that someone may use both the old and the new allowance by unfortunate
transaction ordering. One possible solution to mitigate this race
condition is to first reduce the spender's allowance to 0 and set the
desired value afterwards:
https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729

Emits an {Approval} event._

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 value) external returns (bool)
```

_Moves a `value` amount of tokens from `from` to `to` using the
allowance mechanism. `value` is then deducted from the caller's
allowance.

Returns a boolean value indicating whether the operation succeeded.

Emits a {Transfer} event._

 --- 
### Events:
inherits IERC20:
### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

_Emitted when `value` tokens are moved from one account (`from`) to
another (`to`).

Note that `value` may be zero._

### Approval

```solidity
event Approval(address owner, address spender, uint256 value)
```

_Emitted when the allowance of a `spender` for an `owner` is set by
a call to {approve}. `value` is the new allowance._

## Context

_Provides information about the current execution context, including the
sender of the transaction and its data. While these are generally available
via msg.sender and msg.data, they should not be accessed in such a direct
manner, since when dealing with meta-transactions the account sending and
paying for execution may not be the actual sender (as far as an application
is concerned).

This contract is only required for intermediate, library-like contracts._

### Contract
Context : contracts/LONGD_flattened.sol

Provides information about the current execution context, including the
sender of the transaction and its data. While these are generally available
via msg.sender and msg.data, they should not be accessed in such a direct
manner, since when dealing with meta-transactions the account sending and
paying for execution may not be the actual sender (as far as an application
is concerned).

This contract is only required for intermediate, library-like contracts.

 --- 
### Functions:
### _msgSender

```solidity
function _msgSender() internal view virtual returns (address)
```

### _msgData

```solidity
function _msgData() internal view virtual returns (bytes)
```

### _contextSuffixLength

```solidity
function _contextSuffixLength() internal view virtual returns (uint256)
```

## IERC20Errors

_Standard ERC-20 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-20 tokens._

### Contract
IERC20Errors : contracts/LONGD_flattened.sol

Standard ERC-20 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-20 tokens.

## IERC721Errors

_Standard ERC-721 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-721 tokens._

### Contract
IERC721Errors : contracts/LONGD_flattened.sol

Standard ERC-721 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-721 tokens.

## IERC1155Errors

_Standard ERC-1155 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-1155 tokens._

### Contract
IERC1155Errors : contracts/LONGD_flattened.sol

Standard ERC-1155 Errors
Interface of the https://eips.ethereum.org/EIPS/eip-6093[ERC-6093] custom errors for ERC-1155 tokens.

## ERC20

_Implementation of the {IERC20} interface.

This implementation is agnostic to the way tokens are created. This means
that a supply mechanism has to be added in a derived contract using {_mint}.

TIP: For a detailed writeup see our guide
https://forum.openzeppelin.com/t/how-to-implement-erc20-supply-mechanisms/226[How
to implement supply mechanisms].

The default value of {decimals} is 18. To change this, you should override
this function so it returns a different value.

We have followed general OpenZeppelin Contracts guidelines: functions revert
instead returning `false` on failure. This behavior is nonetheless
conventional and does not conflict with the expectations of ERC-20
applications._

### Contract
ERC20 : contracts/LONGD_flattened.sol

Implementation of the {IERC20} interface.

This implementation is agnostic to the way tokens are created. This means
that a supply mechanism has to be added in a derived contract using {_mint}.

TIP: For a detailed writeup see our guide
https://forum.openzeppelin.com/t/how-to-implement-erc20-supply-mechanisms/226[How
to implement supply mechanisms].

The default value of {decimals} is 18. To change this, you should override
this function so it returns a different value.

We have followed general OpenZeppelin Contracts guidelines: functions revert
instead returning `false` on failure. This behavior is nonetheless
conventional and does not conflict with the expectations of ERC-20
applications.

 --- 
### Functions:
### constructor

```solidity
constructor(string name_, string symbol_) internal
```

_Sets the values for {name} and {symbol}.

All two of these values are immutable: they can only be set once during
construction._

### name

```solidity
function name() public view virtual returns (string)
```

_Returns the name of the token._

### symbol

```solidity
function symbol() public view virtual returns (string)
```

_Returns the symbol of the token, usually a shorter version of the
name._

### decimals

```solidity
function decimals() public view virtual returns (uint8)
```

_Returns the number of decimals used to get its user representation.
For example, if `decimals` equals `2`, a balance of `505` tokens should
be displayed to a user as `5.05` (`505 / 10 ** 2`).

Tokens usually opt for a value of 18, imitating the relationship between
Ether and Wei. This is the default value returned by this function, unless
it's overridden.

NOTE: This information is only used for _display_ purposes: it in
no way affects any of the arithmetic of the contract, including
{IERC20-balanceOf} and {IERC20-transfer}._

### totalSupply

```solidity
function totalSupply() public view virtual returns (uint256)
```

_See {IERC20-totalSupply}._

### balanceOf

```solidity
function balanceOf(address account) public view virtual returns (uint256)
```

_See {IERC20-balanceOf}._

### transfer

```solidity
function transfer(address to, uint256 value) public virtual returns (bool)
```

_See {IERC20-transfer}.

Requirements:

- `to` cannot be the zero address.
- the caller must have a balance of at least `value`._

### allowance

```solidity
function allowance(address owner, address spender) public view virtual returns (uint256)
```

_See {IERC20-allowance}._

### approve

```solidity
function approve(address spender, uint256 value) public virtual returns (bool)
```

_See {IERC20-approve}.

NOTE: If `value` is the maximum `uint256`, the allowance is not updated on
`transferFrom`. This is semantically equivalent to an infinite approval.

Requirements:

- `spender` cannot be the zero address._

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 value) public virtual returns (bool)
```

_See {IERC20-transferFrom}.

Skips emitting an {Approval} event indicating an allowance update. This is not
required by the ERC. See {xref-ERC20-_approve-address-address-uint256-bool-}[_approve].

NOTE: Does not update the allowance if the current allowance
is the maximum `uint256`.

Requirements:

- `from` and `to` cannot be the zero address.
- `from` must have a balance of at least `value`.
- the caller must have allowance for ``from``'s tokens of at least
`value`._

### _transfer

```solidity
function _transfer(address from, address to, uint256 value) internal
```

_Moves a `value` amount of tokens from `from` to `to`.

This internal function is equivalent to {transfer}, and can be used to
e.g. implement automatic token fees, slashing mechanisms, etc.

Emits a {Transfer} event.

NOTE: This function is not virtual, {_update} should be overridden instead._

### _update

```solidity
function _update(address from, address to, uint256 value) internal virtual
```

_Transfers a `value` amount of tokens from `from` to `to`, or alternatively mints (or burns) if `from`
(or `to`) is the zero address. All customizations to transfers, mints, and burns should be done by overriding
this function.

Emits a {Transfer} event._

### _mint

```solidity
function _mint(address account, uint256 value) internal
```

_Creates a `value` amount of tokens and assigns them to `account`, by transferring it from address(0).
Relies on the `_update` mechanism

Emits a {Transfer} event with `from` set to the zero address.

NOTE: This function is not virtual, {_update} should be overridden instead._

### _burn

```solidity
function _burn(address account, uint256 value) internal
```

_Destroys a `value` amount of tokens from `account`, lowering the total supply.
Relies on the `_update` mechanism.

Emits a {Transfer} event with `to` set to the zero address.

NOTE: This function is not virtual, {_update} should be overridden instead_

### _approve

```solidity
function _approve(address owner, address spender, uint256 value) internal
```

_Sets `value` as the allowance of `spender` over the `owner` s tokens.

This internal function is equivalent to `approve`, and can be used to
e.g. set automatic allowances for certain subsystems, etc.

Emits an {Approval} event.

Requirements:

- `owner` cannot be the zero address.
- `spender` cannot be the zero address.

Overrides to this logic should be done to the variant with an additional `bool emitEvent` argument._

### _approve

```solidity
function _approve(address owner, address spender, uint256 value, bool emitEvent) internal virtual
```

_Variant of {_approve} with an optional flag to enable or disable the {Approval} event.

By default (when calling {_approve}) the flag is set to true. On the other hand, approval changes made by
`_spendAllowance` during the `transferFrom` operation set the flag to false. This saves gas by not emitting any
`Approval` event during `transferFrom` operations.

Anyone who wishes to continue emitting `Approval` events on the`transferFrom` operation can force the flag to
true using the following override:

```solidity
function _approve(address owner, address spender, uint256 value, bool) internal virtual override {
    super._approve(owner, spender, value, true);
}
```

Requirements are the same as {_approve}._

### _spendAllowance

```solidity
function _spendAllowance(address owner, address spender, uint256 value) internal virtual
```

_Updates `owner` s allowance for `spender` based on spent `value`.

Does not update the allowance value in case of infinite allowance.
Revert if not enough allowance is available.

Does not emit an {Approval} event._

inherits IERC20Errors:
inherits IERC20Metadata:
inherits IERC20:

 --- 
### Events:
inherits IERC20Errors:
inherits IERC20Metadata:
inherits IERC20:
### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

_Emitted when `value` tokens are moved from one account (`from`) to
another (`to`).

Note that `value` may be zero._

### Approval

```solidity
event Approval(address owner, address spender, uint256 value)
```

_Emitted when the allowance of a `spender` for an `owner` is set by
a call to {approve}. `value` is the new allowance._

## Ownable

_Contract module which provides a basic access control mechanism, where
there is an account (an owner) that can be granted exclusive access to
specific functions.

The initial owner is set to the address provided by the deployer. This can
later be changed with {transferOwnership}.

This module is used through inheritance. It will make available the modifier
`onlyOwner`, which can be applied to your functions to restrict their use to
the owner._

### Contract
Ownable : contracts/LONGD_flattened.sol

Contract module which provides a basic access control mechanism, where
there is an account (an owner) that can be granted exclusive access to
specific functions.

The initial owner is set to the address provided by the deployer. This can
later be changed with {transferOwnership}.

This module is used through inheritance. It will make available the modifier
`onlyOwner`, which can be applied to your functions to restrict their use to
the owner.

 --- 
### Modifiers:
### onlyOwner

```solidity
modifier onlyOwner()
```

_Throws if called by any account other than the owner._

 --- 
### Functions:
### constructor

```solidity
constructor(address initialOwner) internal
```

_Initializes the contract setting the address provided by the deployer as the initial owner._

### owner

```solidity
function owner() public view virtual returns (address)
```

_Returns the address of the current owner._

### _checkOwner

```solidity
function _checkOwner() internal view virtual
```

_Throws if the sender is not the owner._

### renounceOwnership

```solidity
function renounceOwnership() public virtual
```

_Leaves the contract without owner. It will not be possible to call
`onlyOwner` functions. Can only be called by the current owner.

NOTE: Renouncing ownership will leave the contract without an owner,
thereby disabling any functionality that is only available to the owner._

### transferOwnership

```solidity
function transferOwnership(address newOwner) public virtual
```

_Transfers ownership of the contract to a new account (`newOwner`).
Can only be called by the current owner._

### _transferOwnership

```solidity
function _transferOwnership(address newOwner) internal virtual
```

_Transfers ownership of the contract to a new account (`newOwner`).
Internal function without access restriction._

 --- 
### Events:
### OwnershipTransferred

```solidity
event OwnershipTransferred(address previousOwner, address newOwner)
```

## LONGD

### Contract
LONGD : contracts/LONGD_flattened.sol

 --- 
### Functions:
### constructor

```solidity
constructor() public
```

### mint

```solidity
function mint(address to, uint256 amount) public
```

### burn

```solidity
function burn(uint256 amount) public
```

inherits Ownable:
### owner

```solidity
function owner() public view virtual returns (address)
```

_Returns the address of the current owner._

### _checkOwner

```solidity
function _checkOwner() internal view virtual
```

_Throws if the sender is not the owner._

### renounceOwnership

```solidity
function renounceOwnership() public virtual
```

_Leaves the contract without owner. It will not be possible to call
`onlyOwner` functions. Can only be called by the current owner.

NOTE: Renouncing ownership will leave the contract without an owner,
thereby disabling any functionality that is only available to the owner._

### transferOwnership

```solidity
function transferOwnership(address newOwner) public virtual
```

_Transfers ownership of the contract to a new account (`newOwner`).
Can only be called by the current owner._

### _transferOwnership

```solidity
function _transferOwnership(address newOwner) internal virtual
```

_Transfers ownership of the contract to a new account (`newOwner`).
Internal function without access restriction._

inherits ERC20:
### name

```solidity
function name() public view virtual returns (string)
```

_Returns the name of the token._

### symbol

```solidity
function symbol() public view virtual returns (string)
```

_Returns the symbol of the token, usually a shorter version of the
name._

### decimals

```solidity
function decimals() public view virtual returns (uint8)
```

_Returns the number of decimals used to get its user representation.
For example, if `decimals` equals `2`, a balance of `505` tokens should
be displayed to a user as `5.05` (`505 / 10 ** 2`).

Tokens usually opt for a value of 18, imitating the relationship between
Ether and Wei. This is the default value returned by this function, unless
it's overridden.

NOTE: This information is only used for _display_ purposes: it in
no way affects any of the arithmetic of the contract, including
{IERC20-balanceOf} and {IERC20-transfer}._

### totalSupply

```solidity
function totalSupply() public view virtual returns (uint256)
```

_See {IERC20-totalSupply}._

### balanceOf

```solidity
function balanceOf(address account) public view virtual returns (uint256)
```

_See {IERC20-balanceOf}._

### transfer

```solidity
function transfer(address to, uint256 value) public virtual returns (bool)
```

_See {IERC20-transfer}.

Requirements:

- `to` cannot be the zero address.
- the caller must have a balance of at least `value`._

### allowance

```solidity
function allowance(address owner, address spender) public view virtual returns (uint256)
```

_See {IERC20-allowance}._

### approve

```solidity
function approve(address spender, uint256 value) public virtual returns (bool)
```

_See {IERC20-approve}.

NOTE: If `value` is the maximum `uint256`, the allowance is not updated on
`transferFrom`. This is semantically equivalent to an infinite approval.

Requirements:

- `spender` cannot be the zero address._

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 value) public virtual returns (bool)
```

_See {IERC20-transferFrom}.

Skips emitting an {Approval} event indicating an allowance update. This is not
required by the ERC. See {xref-ERC20-_approve-address-address-uint256-bool-}[_approve].

NOTE: Does not update the allowance if the current allowance
is the maximum `uint256`.

Requirements:

- `from` and `to` cannot be the zero address.
- `from` must have a balance of at least `value`.
- the caller must have allowance for ``from``'s tokens of at least
`value`._

### _transfer

```solidity
function _transfer(address from, address to, uint256 value) internal
```

_Moves a `value` amount of tokens from `from` to `to`.

This internal function is equivalent to {transfer}, and can be used to
e.g. implement automatic token fees, slashing mechanisms, etc.

Emits a {Transfer} event.

NOTE: This function is not virtual, {_update} should be overridden instead._

### _update

```solidity
function _update(address from, address to, uint256 value) internal virtual
```

_Transfers a `value` amount of tokens from `from` to `to`, or alternatively mints (or burns) if `from`
(or `to`) is the zero address. All customizations to transfers, mints, and burns should be done by overriding
this function.

Emits a {Transfer} event._

### _mint

```solidity
function _mint(address account, uint256 value) internal
```

_Creates a `value` amount of tokens and assigns them to `account`, by transferring it from address(0).
Relies on the `_update` mechanism

Emits a {Transfer} event with `from` set to the zero address.

NOTE: This function is not virtual, {_update} should be overridden instead._

### _burn

```solidity
function _burn(address account, uint256 value) internal
```

_Destroys a `value` amount of tokens from `account`, lowering the total supply.
Relies on the `_update` mechanism.

Emits a {Transfer} event with `to` set to the zero address.

NOTE: This function is not virtual, {_update} should be overridden instead_

### _approve

```solidity
function _approve(address owner, address spender, uint256 value) internal
```

_Sets `value` as the allowance of `spender` over the `owner` s tokens.

This internal function is equivalent to `approve`, and can be used to
e.g. set automatic allowances for certain subsystems, etc.

Emits an {Approval} event.

Requirements:

- `owner` cannot be the zero address.
- `spender` cannot be the zero address.

Overrides to this logic should be done to the variant with an additional `bool emitEvent` argument._

### _approve

```solidity
function _approve(address owner, address spender, uint256 value, bool emitEvent) internal virtual
```

_Variant of {_approve} with an optional flag to enable or disable the {Approval} event.

By default (when calling {_approve}) the flag is set to true. On the other hand, approval changes made by
`_spendAllowance` during the `transferFrom` operation set the flag to false. This saves gas by not emitting any
`Approval` event during `transferFrom` operations.

Anyone who wishes to continue emitting `Approval` events on the`transferFrom` operation can force the flag to
true using the following override:

```solidity
function _approve(address owner, address spender, uint256 value, bool) internal virtual override {
    super._approve(owner, spender, value, true);
}
```

Requirements are the same as {_approve}._

### _spendAllowance

```solidity
function _spendAllowance(address owner, address spender, uint256 value) internal virtual
```

_Updates `owner` s allowance for `spender` based on spent `value`.

Does not update the allowance value in case of infinite allowance.
Revert if not enough allowance is available.

Does not emit an {Approval} event._

inherits IERC20Errors:
inherits IERC20Metadata:
inherits IERC20:

 --- 
### Events:
inherits Ownable:
### OwnershipTransferred

```solidity
event OwnershipTransferred(address previousOwner, address newOwner)
```

inherits ERC20:
inherits IERC20Errors:
inherits IERC20Metadata:
inherits IERC20:
### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

_Emitted when `value` tokens are moved from one account (`from`) to
another (`to`).

Note that `value` may be zero._

### Approval

```solidity
event Approval(address owner, address spender, uint256 value)
```

_Emitted when the allowance of a `spender` for an `owner` is set by
a call to {approve}. `value` is the new allowance._

