# Ephemeral DH Key Exchange

<b>Ephemeral DH</b><br>
Ephemeral DH is different from static, ie classical DH. Static DH obtains the same session key in each session for a long time and uses this session key. With the development of various algorithms over time, these keys can be solved. In addition, once the attacker has the session key, he can capture and decrypt all secret conversations made in the past through this session key. In Ephemeral DH, it provides obtaining different session keys in different sessions. Thus, even if he aggressively obtains the session key, he cannot access any historical information. This ensures Forward Secrecy (FS).
<br><br>
Codes has been compiled in the C programming language and is written for the practicalization of the Ephemeral Diffie Hellman algorithm.
