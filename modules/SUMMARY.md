[Nightmare](../README.md)

- [Introduction](./00-intro/readme.md)
  - [Assembly](./01-intro_assembly/assembly/readme.md)
  - [Reversing Assembly](./01-intro_assembly/reversing_assembly/readme.md)
  - [Reversing with GHIDRA](./02-intro_tooling/ghidra/readme.md)
  - [Debugging with GDB](./02-intro_tooling/gdb-gef/readme.md)
  - [Scripting with Python pwntools](./02-intro_tooling/pwntools/readme.md)
  - [Beginner Reversing](./03-beginner_re/csaw18_x86tour_pt1/readme.md)
    - [CSAW'19: Beleaf](./03-beginner_re/csaw19_beleaf/readme.md)
    - [Helithumper RE](./03-beginner_re/helithumper_re/readme.md)
    - [Pico'18: Strings](./03-beginner_re/pico18_strings/readme.md)

- [Stack Buffer Overflows](./04-bof_variable/csaw18_boi/Readme.md)
  - [TAMU'19: Pwn1](./04-bof_variable/tamu19_pwn1/Readme.md)
  - [TokyoWesterns'17: JustDoIt](./04-bof_variable/tw17_justdoit/readme.md)
  - [CSAW'16: Warmup](./05-bof_callfunction/csaw16_warmup/readme.md)
  - [CSAW'18: Getit](./05-bof_callfunction/csaw18_getit/readme.md)
  - [TU'17: Vulnchat](./05-bof_callfunction/tu17_vulnchat/readme.md)
    - [ASLR/PIE](./5.1-mitigation_aslr_pie/readme.md)
  - [CSAW'17: Pilot](./06-bof_shellcode/csaw17_pilot/readme.md)
  - [TAMU'19: Pwn3](./06-bof_shellcode/tamu19_pwn3/readme.md)
  - [TU'18: Shellaeasy](./06-bof_shellcode/tu18_shellaeasy/readme.md)
    - [NX/XN/DEP](./6.1-mitigation_nx/readme.md)
  - [BKP'16: SimpleCalc](./07-bof_static/bkp16_simplecalc/readme.md)
  - [DCQuals'16: Feedme](./07-bof_static/dcquals16_feedme/readme.md)
  - [DCQuals'19: Speedrun1](./07-bof_static/dcquals19_speedrun1/readme.md)
    - [Canaries/Cookies](./7.1-mitigation_canary/readme.md)
    - [RELRO](./7.2-mitigation_relro/readme.md)
  - [CSAW'19: Babyboi](./08-bof_dynamic/csaw19_babyboi/readme.md)
  - [CSAW Quals'17: SVC](./08-bof_dynamic/csawquals17_svc/readme.md)
  - [FB'19: Overfloat](./08-bof_dynamic/fb19_overfloat/readme.md)
  - [HS'19: Storytime](./08-bof_dynamic/hs19_storytime/readme.md)

- [Format Strings](./fmt.md)
  - [Backdoor'17: bbpwn](./10-fmt_strings/backdoor17_bbpwn/readme.md)
  - [PicoCTF'18: echo](./10-fmt_strings/pico18_echo/readme.md)
  - [TokyoWesterns'16: Greeting](./10-fmt_strings/tw16_greeting/readme.md)

- [Array Indexing](./indexing.md)
  - [CSAW'18: DoubleTrouble](./11-index/csaw18_doubletrouble/readme.md)
  - [DCQ'16: XKCD](./11-index/dcq16_xkcd/readme.md)
  - [SunshineCTF'17: Alt. Solution](./11-index/sunshinectf2017_alternatesolution/readme.md)
  - [SwampCTF'19: Dreamheaps](./11-index/swampctf19_dreamheaps/readme.md)

- [Bad Seed](./randomness.md)
  - [H3: Time](./09-bad_seed/h3_time/readme.md)
  - [HSCTF'19: Tuxtalkshow](./09-bad_seed/hsctf19_tuxtalkshow/reamde.md)
  - [SunshineCTF'17: Prepared](./09-bad_seed/sunshinectf17_prepared/readme.md)

- [Z3 & Symbolic Execution (angr)](./z3_angr.md)
  - [HS'19: abyte](./12-z3/hs19_abyte/readme.md)
  - [TokyoWesterns'17: revrevrev](./12-z3/tokyowesterns17_revrevrev/readme.md)
  - [TUCTF: Future](./12-z3/tuctf_future/readme.md)
  - [DEFCamp: r100](./13-angr/defcamp_r100/readme.md)
  - [PlaidCTF'19: icancount](./13-angr/plaid19_icancount/readme.md)
  - [SecurityFest Fairlight](./13-angr/securityfest_fairlight/readme.md)

- [Return Oriented Programming (ROP)](./rop.md)
  - [Partial Overwrite](./15-partial_overwrite/readme.md)
    - [Hack.lu'15: stackstuff](./15-partial_overwrite/hacklu15_stackstuff/readme.md)
    - [TAMU'19: pwn2](./15-partial_overwrite/tamu19_pwn2/readme.md)
    - [TUCTF'17: vulnchat2](./15-partial_overwrite/tuctf17_vulnchat2/readme.md)
  - [Stack Pivoting](./17-stack_pivot/readme.md)
    - [DCQuals'19: speedrun4](./17-stack_pivot/dcquals19_speedrun4/readme.md)
    - [Insomnihack'18: onewrite](./17-stack_pivot/insomnihack18_onewrite/readme.md)
    - [SECCON'19: sum](./17-stack_pivot/seccon19_sum/readme.md)
    - [XCTF'16: b0verflow](./17-stack_pivot/xctf16_b0verflow/readme.md)
  - [SIGROP (SROP)](./16-srop/readme.md)
    - [BackdoorCTF: funsigals](./16-srop/backdoor_funsignals/readme.md)
    - [CSAW'19: smallboi](./16-srop/csaw19_smallboi/readme.md)
    - [InCTF'17: stupidrop](./16-srop/inctf17_stupidrop/readme.md)
    - [SwampCTF'19: syscaller](./16-srop/swamp19_syscaller/readme.md)
  - [ret2csu](./18-ret2_csu_dl/readme.md)
    - [0CTF'18: babystack](./18-ret2_csu_dl/0ctf18_babystack/readme.md)
    - [ROPEmporium](./18-ret2_csu_dl/ropemporium_ret2csu/readme.md)
  - [ret2system](./14-ret_2_system/readme.md)
    - [ASIS'17: marymorton](./14-ret_2_system/asis17_marymorton/readme.md)
    - [HXP'18: poorCanary](./14-ret_2_system/hxp18_poorCanary/readme.md)
    - [TUCTF: guestbook](./14-ret_2_system/tu_guestbook/readme.md)

- [Heap Exploitation](./25-heap/Readme.md)
  - [Double Frees](./27-edit_free_chunk/double_free_explanation/readme.md)
  - [Heap Consolidation](./27-edit_free_chunk/heap_consolidation_explanation/readme.md)
  - [Use-after-Frees](./27-edit_free_chunk/uaf_explanation/readme.md)
  - [Protostar: heap0](./24-heap_overflow/protostar_heap0/readme.md)
  - [Protostar: heap1](./24-heap_overflow/protostar_heap1/readme.md)
  - [Protostar: heap2](./24-heap_overflow/protostar_heap2/reamdme.md)
  - [unlink() Exploitation](./30-unlink/unlink_explanation/readme.md)
    - [HITCON'14: stkof](./30-unlink/hitcon14_stkof/readme.md)
    - [ZCTF'16: note2](./30-unlink/zctf16_note2/readme.md)
  - [Heap Grooming](./26-heap_grooming/explanation_heap_grooming/readme.md)
    - [PicoCTF: areyouroot](./26-heap_grooming/pico_areyouroot/readme.md)
    - [SwampCTF'19: Heap Golf](./26-heap_grooming/swamp19_heapgolf/readme.md)
  - [Fastbin Attack](./28-fastbin_attack/explanation_fastbinAttack/readme.md)
    - [0CTF: babyheap](./28-fastbin_attack/0ctf_babyheap/readme.md)
    - [CSAW'17: Auir](./28-fastbin_attack/csaw17_auir/readme.md)
  - [Unsortedbin Attack](./31-unsortedbin_attack/unsorted_explanation/readme.md)
    - [0CTF'16: zerostorage](./31-unsortedbin_attack/0ctf16_zerostorage/README.md)
    - [HITCON: magicheap](./31-unsortedbin_attack/hitcon_magicheap/readme.md)
  - [Largebin Attack (part 1)](./32-largebin_attack/largebin_explanation0/README.md)
  - [Largebin Attack (part 2)](./32-largebin_attack/largebin_explanation1/readme.md)
  - [GLibc Tcache](./29-tcache/tcache_explanation/readme.md)
    - [DCQuals'19: babyheap](./29-tcache/dcquals19_babyheap/readme.md)
    - [PlaidCTF'19: cpp](./29-tcache/plaid19_cpp/readme.md)
    - [CSAW'19: Popping Caps 1](./44-more_tcache/csaw19_popping_caps0/readme.md)
    - [CSAW'19: Popping Caps 2](./44-more_tcache/csaw19_popping_caps1/readme.md)
  - [House of Spirit](./39-house_of_spirit/house_spirit_exp/readme.md)
    - [Hack.lu'14: Oreo](./39-house_of_spirit/hacklu14_oreo/readme.md)
  - [House of Lore](./40-house_of_lore/house_lore_exp/readme.md)
  - [House of Force](./41-house_of_force/house_force_exp/readme.md)
    - [BKP'16: Cookbook](./41-house_of_force/bkp16_cookbook/readme.md)
  - [House of Einherjar](./42-house_of_einherjar/house_einherjar_exp/readme.md)
  - [House of Orange](./43-house_of_orange/house_orange_exp/Readme.md)
  - [Miscellaneous](./33-custom_misc_heap/readme.md)
    - [CSAW'17: Minesweeper](./33-custom_misc_heap/csaw17_minesweeper/readme.md)
    - [CSAW'18: alienVSsamurai](./33-custom_misc_heap/csaw18_alienVSsamurai/readme.md)
    - [CSAW'19: Traveller](./33-custom_misc_heap/csaw19_traveller/readme.md)

- [Integer Overflows](./35-integer_exploitation/readme.md)
  - [sploitFUN: vuln](./35-integer_exploitation/int_overflow_post/readme.md)
  - [Puzzle](./35-integer_exploitation/puzzle/readme.md)
  - [Signed vs. Unsigned](./35-integer_exploitation/signed_unsigned/readme.md)

- [FILE Exploitation](./37-fs_exploitation/readme.md)
  - [SwampCTF'19: Bad File](./37-fs_exploitation/swamp19_badfile/readme.md)

- [Grab Bag](./grabbag.md)
  - [Shellcoding](./19-shellcoding_pt1/readme.md)
    - [CSAW'18: Shellpointcode](./19-shellcoding_pt1/csaw18_shellpointcode/readme.md)
    - [DCQuals'19: S3](./19-shellcoding_pt1/defconquals19_s3/readme.md)
    - [DCQuals'19: S6](./19-shellcoding_pt1/defconquals19_s6/readme.md)
  - [Patching](./20-patching_and_jumping/readme.md)
    - [CSAW Quals'16: gametime](./20-patching_and_jumping/csawquals16_gametime/readme.md)
    - [DCQuals'18: ELFCrumble](./20-patching_and_jumping/dcquals18_elfcrumble/readme.md)
    - [Plaid'19: PPP](./20-patching_and_jumping/plaid19_ppp/readme.md)
  - [.NET](./21-dot_net/readme.md)
    - [Bikinibonanza](./21-dot_net/bikinibonanza/readme.md)
    - [CSAW'13: DotNetReversing](./21-dot_net/dot_net/readme.md)
    - [Whitehat'18: re06](./21-dot_net/whitehat18_re06/readme.md)
  - [Obfuscation](./36-obfuscated_reversing/readme.md)
    - [BKP'16: Unholy](./36-obfuscated_reversing/bkp16_unholy/Readme.md)
    - [CSAW'15: Wyvern](./36-obfuscated_reversing/csaw15_wyvern/readme.md)
    - [CSAW'17: Prophecy](./36-obfuscated_reversing/csaw17_prophecy/Readme.md)
    - [MOVfuscation](./22-movfuscation/readme.md)
      - [ASIS'18: babyc](./22-movfuscation/asis18_babyc/readme.md)
      - [RECON: movfuscated](./22-movfuscation/recon_movfuscated/readme.md)
      - [SwampCTF'19: Future Fun](./22-movfuscation/swamp19_future/readme.md)
  - [Custom Architecture](./23-custom_architecture/readme.md)
    - [H3Machine (part 1)](./23-custom_architecture/h3_h3machine0/readme.md)
    - [H3Machine (part 2)](./23-custom_architecture/h3_h3machine1/readme.md)
    - [H3Machine (part 3)](./23-custom_architecture/h3_h3machine2/readme.md)
    - [H3Machine (part 4)](./23-custom_architecture/h3_h3machine3/readme.md)
  - [Emulation](./34-emulated_targets/readme.md)
    - [CSAW'15: Hackingtime](./34-emulated_targets/csaw15_hackingtime/readme.md)
    - [CSAW'17: Realism](./34-emulated_targets/csaw17_realism/readme.md)
    - [CSAW'18: x86 Pt.2](./34-emulated_targets/csaw18_x86_pt2/readme.md)
  - [Uninitialized Variables](./38-grab_bad/uninit_vars/readme.md)
  - [CSAW'18: Doubletrouble](./38-grab_bad/csaw18_doubletrouble/readme.md)
  - [CSAW'19: Gibberishcheck](./38-grab_bad/csaw19_gibberishCheck/readme.md)
  - [HackIM'19: Shop](./38-grab_bad/hackim19_shop/readme.md)

[What's Next](./next/readme.md)
[References](./references/readme.md)