# kalkulator
Kalkulator sederhana yang dibuat ketika belajar DOM dan Object javascript

<table border="0" cellspacing="3">
  <tr>
    <td colspan="4"><input type="text" id="input" maxlength="18" onkeydown="kalk.inputKeyboard()" readonly="readonly"></td>
    <td><button class="hapus" onclick="kalk.input('&lt;')">&lt;</button></td>
  </tr>
  <tr>
    <td><button class="angka" onclick="kalk.input('7')">7</button></td>
    <td><button class="angka" onclick="kalk.input('8')">8</button></td>
    <td><button class="angka" onclick="kalk.input('9')">9</button></td>
    <td colspan="2"><button class="hapus wide bersih" onclick="kalk.input('c')">Bersih</button></td>
  </tr>
  <tr>
    <td><button class="angka" onclick="kalk.input('4')">4</button></td>
    <td><button class="angka" onclick="kalk.input('5')">5</button></td>
    <td><button class="angka" onclick="kalk.input('6')">6</button></td>
    <td><button class="operasi" onclick="kalk.input('+')">+</button></td>
    <td><button class="operasi" onclick="kalk.input('-')">-</button></td>
  </tr>
  <tr>
    <td><button class="angka" onclick="kalk.input('1')">1</button></td>
    <td><button class="angka" onclick="kalk.input('2')">2</button></td>
    <td><button class="angka" onclick="kalk.input('3')">3</button></td>
    <td><button class="operasi" onclick="kalk.input('x')">x</button></td>
    <td><button class="operasi" onclick="kalk.input('/')">/</button></td>
  </tr>
  <tr>
    <td><button class="opsi" onclick="kalk.input('switch')">-/+</button></td>
    <td><button class="angka" onclick="kalk.input('0')">0</button></td>
    <td><button class="opsi" onclick="kalk.input('.')">.</button></td>
    <td colspan="2"><button class="hasil wide" onclick="kalk.input('=')">=</button></td>
  </tr>
  <tr id="last">
    <td colspan="5"><b id="row">&gt;</b> log I/O
      <div id="log" name="log"></div>
    </td>
  </tr>
</table>
