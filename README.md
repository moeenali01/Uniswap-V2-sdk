# Contract Addresses and Information

Here are some important addresses and contract details:

- **Factory Contract**: `0xf91F0e3417574e9778B57c62c60C3A520C19fAe3`
- **WETH**: `0x1d181cBd1825e9eBC6AD966878D555A7215FF4F0`
- **Router**: `0x36211d76f2A175159dd205D98e40A38D71d8522E`
- **Hex**: `0x98f26ce9cce0e963cb9909ef6d6874753cab44c9c061f1fcf45e7b52c2ee59ba`
- **Multicall**: `0x24E7f67b7789555EaE221317Be9BB4B6c67a0a54`

# Network Information

- **Network**: Holesky Testnet
- **Chain ID**: `17000`
- **RPC URL**: `https://rpc.holesky.network`


# Uniswap SDK

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![Actions Status](https://github.com/Uniswap/uniswap-sdk/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-sdk)
[![npm version](https://img.shields.io/npm/v/@uniswap/sdk/latest.svg)](https://www.npmjs.com/package/@uniswap/sdk/v/latest)
[![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/minzip/@uniswap/sdk/latest.svg)](https://bundlephobia.com/result?p=@uniswap/sdk@latest)

In-depth documentation on this SDK is available at [uniswap.org](https://uniswap.org/docs/v2/SDK/getting-started/).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/Uniswap/uniswap-sdk.git
```

Move into the uniswap-sdk working directory

```sh
cd uniswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
