# webauthn-demo-browseronly

* WebAuthnの雑なデモです。
* RP側の処理も全部ブラウザ内でやってます。
  * WebAuthnの一連の流れを全部ブラウザ側で確認できるものを作ろう、という目的のものです。
  * RP側の処理は iframe の rp.html でやってます。
  * 署名の検証はWeb Crypto APIを使っています。
* 参考文献
  * https://slides.com/fidoalliance/jan-2018-fido-seminar-webauthn-tutorial#/
  * https://my-transistor.booth.pm/items/1157260
